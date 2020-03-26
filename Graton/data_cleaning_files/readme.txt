Files:

1. product.txt and table_formats.pdf
Downloaded Feb 2020 from https://apps.cdpr.ca.gov/docs/label/labelque.cfm
Used to convert pounds = Gallons * Density * Specific Gravity of the product


2. DistinctAddresses_geocodio.xlsm
Site locations were translated from street address to lat,lon using https://dash.geocod.io/import

sample python code:
# Download distinct addresses
temp = alldf.loc[:, ["Site Name", 'city', 'state', 'zipcode']].groupby("Site Name").first()
temp.reset_index(inplace=True, drop=False)

temp.to_csv("DistinctAddresses.csv"
                 ,index=False,sep="\t"
                 , header=True
                 , encoding='utf-8'
                 , quoting=csv.QUOTE_NONNUMERIC)

# Translate the csv file using https://dash.geocod.io/import
# Save the geocoded data locally as DistinctAddresses_geocodio.xlsm

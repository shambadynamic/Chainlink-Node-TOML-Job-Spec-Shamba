# Chainlink Node TOML Job Spec Shamba
 A TOML job spec for serving Shamba Geospatial data

# External Adapter that works with this Job Spec

 https://github.com/shambadynamic/geostatsExternalAdapter

# What to replace

 name = "your-job-name"

 contractAddress = "Your-oracle-address"

 fetch        [method=POST type="bridge" name="your-bridge-name"...

 submit_tx    [type="ethtx" to="Your-oracle-address"...

# What is returned on-chain
 int256   (Geo-API response value multiplied by 10**18)
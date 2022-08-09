How to List All Subscriptions: 
 az account list -o table
 
# get the current default subscription using show
az account show --output table

# change the active subscription using the subscription name
az account set --subscription "My Demos"

# change the active subscription using the subscription ID
az account set --subscription "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"

# change the active subscription using a variable

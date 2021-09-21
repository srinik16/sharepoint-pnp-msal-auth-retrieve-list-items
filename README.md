# sharepoint-pnp-msal-auth-retrieve-list-items
# SharePoint SPFx webpart with PnP MSAL library Get List Items
# Provide admin consent to read sharepoint from Azure AAD 
# Remember to give correct exact Redirect URI as is you have given in AAD registration under Authentication section
# update below two props in Manifest file in Azure AAD
	"oauth2AllowIdTokenImplicitFlow": true,
	"oauth2AllowImplicitFlow": true,
# gulp serve
# To build and package, follow below steps
# > gulp clean --ship
# > gulp build --ship
# > gulp bundle --ship
# > gulp package-solution --ship

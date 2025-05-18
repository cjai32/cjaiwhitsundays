

# Lookbook by CJ Alava

[Store Link](https://chrisvincent-development.myshopify.com/?_ab=0&_bt=eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaEpJaXRqYUhKcGMzWnBibU5sYm5RdFpHVjJaV3h2Y0cxbGJuUXViWGx6YUc5d2FXWjVMbU52YlFZNkJrVlUiLCJleHAiOiIyMDI1LTA1LTE4VDE5OjQwOjQxLjI3NFoiLCJwdXIiOiJwZXJtYW5lbnRfcGFzc3dvcmRfYnlwYXNzIn19--2c802a13caf8bf498335d5c426afbb8d224772df&_fd=0&_sc=1&key=aed2f6294a54c9d4b09a93f0d8752ea6f5334a45764ace2856c071b21b8e4abe&preview_theme_id=178533269811).


Password: `cjva`

## Documentation

- Made with Dawn and Shopify CLI
- Features are made with native Shopify Featured


### Lookbook section requirements

- Created a new section in Shopify Theme Customizer for a Lookbook section
- Allow the lookbook section to be added to any page and customized by theme settings.
- Display lookbooks on product pages if the product appears inside one of the lookbooks
- Ensure the Lookbook appears in a designated section on the product page.

### Notes

- The lookbook section is powered mainly by Shopify Metaobjects, To edit the lookbook metaobject, go to Content -> Metaobjects -> Lookbook. See recording: https://jmp.sh/tq0zWkCK
  - The lookbook metaobjects has a title, description, highlight image and a list of products.
  - Added a highlight image to better highlight the section.

- The lookbook section has been made with the slider component from Dawn.

- The lookbook section has a manual selection of Lookbook metaobject entry through a `metaobject` setting which can be used in all pages: https://jmp.sh/cHJfWm6B

- The on PDP have been consolidated into one section, A theme customizer setting is added to cater the PDP Lookbook section.
  - For PDP, There is a `Lookbook source` setting that is used. Auto Detect will only work on PDP. See recording: https://jmp.sh/Ggti6DaA
  - We do the Auto Detect by checking if product is part of any lookbook by looping through the metaobjects entries on lookbook type
  - We render the lookbook section based on the lookbook entry we got



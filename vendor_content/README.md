# Create a new Vendor
1. Ensure you have a most recent copy of the repository. Refer to https://github.com/nthnthcandrew/Falcon-Logscale-Community-Content#quick-start for an overview of working with Git
2. Copy the template folder for new vendor content and rename appropiately and in alignment with naming standards
3. Update package contents as required [INSERT HERE STEPS]
4. Build the package by following the steps listed here [LINK TO BUILD STEPS]
# Update an existing Vendor
5. Add, Commit and Push to create a new Pull Request for Approval.
[AS ABOVE BUT MODIFYING AN EXISTING PACKAGE]
# Build a package
Packages are a zip file containing a collection of LogScale artifacts that align to a set of standards and organised in a given folder structure as detailed here - [INSERT LINK TO STANDARDS]
1. Open up a terminal window
2. Change to the directory of the vendor or use case that you want to create or update an existing packge
3. Issue the following command to create a package, esuring you specify a a name for the package zip file in alignment with naming standards

   > zip <Vendor_Product_Subproduct>.zip actions alerts dashboards data parsers queries scheduled searches LICENSE manifest.yaml README.md  

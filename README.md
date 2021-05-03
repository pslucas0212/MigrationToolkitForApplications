# DRAFT - Migration Toolkit For Applications - DRAFT

Updated: 2021-04-29

An Overview of installing and using Red Hat Migration Toolkit for Applicaitons

- Download the Migration Toolkit for Applications (MTA) from the [download page](https://developers.redhat.com/products/mta/download)
  - For this exercise I'm downloading the Web Console version to run on my laptop.
  - Note: To download MTA, you'll need a Red Hat customer account.  There is no charge to create account if you don't already have a Red Hat customer account

- Unzip the downloaded zip file in a directory of your choice
        
      # unzip migrationtoolkit-mta-web-distribution-5.1.3-with-authentication.zip

- Change to the directory where you MTA is located and launch MTA with script appropriate to your OS.
  - On the Mac run:
  
        # ./run_mta.sh

- To launch MTA, goto a browser and enter this url: http://localhost:8080/mta-ui


## Using MTA

- Gather you artifact to analyze which could be raw source files or a binary
- On the sidebar menu, click Projects and chose Create a project.  Name your project and optionally add a description.  Click the Next button.
- On the Add Applications step, browse or drag your artifact for analysis and click the Next button
- On the Select transformation target page, chose one or more tiles representing your "target" deployment platform.  Click the next button.  Refer to the [Migration Toolkit for Applications use cases and migration paths ](https://developers.redhat.com/products/mta/use-cases) to see currently supported transformation use cases.
- 
--
## References

- [Migration Toolkit for Applications Overview](https://developers.redhat.com/products/mta/overview)
- Current use cases supported by MTA - [Migration Toolkit for Applications use cases and migration paths ](https://developers.redhat.com/products/mta/use-cases)

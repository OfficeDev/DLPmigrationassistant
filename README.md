# Migration Assistant for Microsoft DLP 


## What is Migration Assistant for Microsoft DLP?

The MAMD tool is a Windows based desktop application that will migrate your DLP policies from other DLP platforms to our Unified DLP platform. 

Our tool takes you through a simple five-step migration process. It accepts Symantec DLP policy XML exports, performs mapping, and creates equivalent Unified DLP policies through PowerShell scripts.

You can safely use the MAMD tool to create DLP policies in test mode, which does not affect your live data or interact with current environment. 

[**Download the Migration Assistant for Microsoft DLP**](https://aka.ms/DownloadMDMA)

## Migration tasks that MAMD performs

MAMD takes over many of the difficult or tedious tasks involved in a DLP migration project:

-	In traditional migration scenario, you need to perform feasibility analysis between source & target DLP platforms, map features, migrate policies manually, and test and tweak DLP policies. Your migrated DLP policies can be up and running within minutes of starting the MAMD process.
- With MAMD, you can scale up your migration project quickly from moving a single policy manually to multiple policies at the same time.
- MAMD automatically identifies Sensitive Information Types (SITs) or Data Identifiers in source policies and creates Custom SITs in your Microsoft tenant moving over all your custom regular expressions and keywords in a few clicks.
- MAMD detects which conditions, exclusions & actions are currently being used in source policies and automatically creates new rules with the same conditions, exclusions & actions.
- MAMD provides you with a detailed migration report with policy wise migration status and recommendations.
- MAMD ensures that your DLP policy migration project is completely private and takes place within the boundaries of your organization.
- MAMD supports policy migration from Symantec Data Loss Prevention 15.7 or earlier.



## How does MAMD work?

![Picture1](https://user-images.githubusercontent.com/69503744/154880938-405ee271-482b-4dca-8f41-30017d64758c.png)

During a given instance of migration, the Migration Assistant for Microsoft DLP works in five phases:

1.  **Input:** MAMD ingests one or more Symantec DLP policy XML files.

2.	**Analyze:** MAMD interprets the files & identifies Symantec DLP policy constructs.

3.	**Rationalize:** MAMD maps the identified Symantec DLP policy constructs to Unified DLP capabilities. It performs validations for Unified DLP platform limitations.

4.	**Migrate:** MAMD executes PowerShell scripts for the DLP scenarios identified & supported by the UDLP platform. 

5.	**Reporting:** MAMD provides the user with a detailed migration report about which policies were migrated successfully, partially and/or not migrated. It also provides recommendations to improve the migration fidelity further.


## Provide Feedback & Report Bugs

Please share feedback with us using this [feedback form](https://aka.ms/MDMAFeedback).

To report errors & any feature requests with us by opening a new issue in this Github repository. Alternatively, you can reach out to us at cxe-help@microsoft.com or via your CXE / Fasttrack / Microsoft partner to share your feedback and suggestions.



## Telemetry Notice

### Data Collection
This software may collect information about you and your use of the software and send it to Microsoft. Microsoft may use this information to provide services and improve our products and services. If you wish to turn off telemetry, please reach out to us and we will provide you with a separate version of tool with telemetry turned off. There are also some features in the software that may enable you and Microsoft to collect data from users of your applications. If you use these features, you must comply with applicable law, including providing appropriate notices to users of your applications together with a copy of Microsoft's privacy statement. Our privacy statement is located at https://go.microsoft.com/fwlink/?LinkID=824704. You can learn more about data collection and use in the help documentation and our privacy statement. Your use of the software operates as your consent to these practices.



## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

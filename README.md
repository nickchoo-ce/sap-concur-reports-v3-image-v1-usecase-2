# SAP Concur Client Web Services – Reports/Entries v3 to Image v1 (Retrieve Only)

## Description

This repository provides **clean, realistic JSON samples** that demonstrate how to retrieve PDF receipt images from **SAP Concur** by first using **Reports v3 / Entries v3 API** to obtain a `ReportID or EntryID`, then calling **Image v1 API** to fetch the receipt.

> Authentication first → Reports v3 (or Entries v3) → Image v1 (GET by ReportID or EntryID).

## APIs Used
| API          | Purpose                                    | Reference |
|--------------|--------------------------------------------|-----------|
| Reports v3   | Get report details and ReportID      | https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html |
| Entries v3   | Get expense entry details and EntryID| https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html |
| Image v1     | Retrieve receipt by Report or EntryID                | https://developer.concur.com/api-reference/image/v1.image.html |

## Requirements

In order to use this repository you will need

1. The Web Service Administration role within SAP Concur (to be able to create SAP Concur applications)
2. Postman (to be able to use the files included in this repository)
3. Have downloaded / installed the Authentication Postman collection [found here](https://github.com/SAP-samples/concur-web-services-authentication).

## Known Issues
No known issues.

## How to obtain support
This project is provided "as-is", with no expected changes or support. The complete Reports, Entries v3 and Image v1 documentation can be found above "APIs Used".

For additional information, please [refer to this documentation](https://developer.concur.com/tools-support/support.html).

## Contributing
This repository is provided "as-is".

## License
Copyright (c) 2025 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](./LICENSE) file.

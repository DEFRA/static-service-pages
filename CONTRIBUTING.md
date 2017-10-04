# Contributing

This project is used by multiple services. Check with the technical leads for those services before amending any existing assets or pages. If you are unsure who they are, or unsure about working with this project, contact [Ben Sagar](https://github.com/bensagar-ea) or [Alan Cruikshanks](https://github.com/Cruikshanks).

All contributions should be submitted on a pull request and follow the process outlined in [DST-guides](https://github.com/DEFRA/dst-guides/blob/master/process/pull_request.md).

## Adding new pages

If you are just adding new pages, there is little risk to existing services so go right ahead. However stick to the following conventions.

- Place front office pages in the [/front-office](/front-office) folder
- Place back office pages in the [/back-office](/back-office) folder
- Name your pages using the pattern [service acronym]-[back or front office]-[type of page].html
- Try to mirror what over services have done with their content. This will help give consistency across services
- Update the [index.html](/index.html) in the root of the folder with links to your new pages

If your service requires you to break one of these conventions though, don't be afraid to do so. Explain the reason why in the PR and document the reason here.

## Convention breaks

### PAFS back office

You'll find the back office pages for the **Project application and funding** service in the [front-office](/front-office) folder. This is because though the service does have a back office system, they have chosen to use the external [GOV.UK template](https://github.com/alphagov/govuk_template) rather than the internal [Admin template](https://github.com/alphagov/govuk_admin_template) for it.

Because of this it makes sense to place the back office pages in the same folder as the front office pages, rather than move front office assets to the back office just to support these 2 pages.

### Data returns back office

The data returns service provides users the ability to upload data to our internal systems. As such there is no back office and hence no back office pages.

### Waste permits back office

Microsoft Dynamics will be used for the back office in Waste permits, and therefore no back office pages are needed.

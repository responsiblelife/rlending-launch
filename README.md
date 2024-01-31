# Launching RLending Customer & Adviser

## PRs (Pull Requests)

- [ ] PR for RLending Customer: [PR #377](https://github.com/responsiblelife/rer-website-futureproof/pull/377)
- [ ] PR for Adviser Site: [PR #380](https://github.com/responsiblelife/rer-website-futureproof/pull/380)
- [ ] PR for Adviser Products: [PR #382](https://github.com/responsiblelife/rer-website-futureproof/pull/382)

*The PRs for the customer site seems to have some extra commits which I have no clue how they've come in so feel free to drag me into a call 
## SQL Statements and Descriptions

| S.No | SQL Query | Description |
|------|-----------|-------------|
| 1 | `UPDATE `responsible_lending_development`.`site_themes`  SET  `secondary_color` = '#002D72' WHERE (`id` = '7');` | Updates the theme secondary color to the new RLending blue. |
| 2 | `UPDATE `responsible_lending_development`.`site_themes`  SET  `primary_color` = '#6F3279' WHERE (`id` = '7');` | Updates the theme primary color to a new shade of purple. |
| 3 | `UPDATE `responsible_lending_development`.`site_pages`  SET  `meta_description` = 'Customers can find out more about the exclusive providers of the Royal London Equity Release product range.' WHERE (`id` = '102'); UPDATE ` responsible_lending_development`.`site_pages`  SET  `meta_title` = 'Responsible Lending: Quality equity release products for homeowners over 55' WHERE (`id` = '102');` | Update meta title and description for homepage. |
| 4 | `INSERT INTO `responsible_lending_development`.`site_pages` (`domain`, `url`, `partner_id`, `type`, `action`, `header`, `footer`, `meta_title`, `meta_description`, `index_yn`, `live_yn`) VALUES ('www.responsiblelending.co.uk', '/customer/cost-of-equity-release', '7', 'Content\\Rlending', 'costOfEquityReleaseCustomer', 'rlending', 'rlending', 'Cost of equity release estimator.', 'Calculate your customer's cost of borrowing with our equity release estimator.', '1', '1'); UPDATE `responsible_lending_development`.`site_pages`   SET   `meta_description` = 'Find out how much equity you could release from your home.' WHERE (`id` = '326');` | Create Results page for the customer site and update the meta description for a specific page. |
| 5    | `UPDATE responsible_lending_development.site_pages   SET   page_title = 'Responsible Lending \| Who are Responsible Lending', meta_title = 'Who are Responsible Lending?', meta_description = 'Find out about the lender who puts their customers first.' WHERE (id = '107');` |       Update Meta title and description for the /about-us page      |
| 6    | `UPDATE responsible_lending_development.site_pages SET page_title = 'Responsible Lending \| Equity Release Explained', meta_title = 'What can equity release do for you?', meta_description = 'Learn about the potential wealth that is held in your property.' WHERE (id = '108');` | Updates meta title and meta description for /equity-release-explained page. |
| 7    | `INSERT INTO responsible_lending_development.site_pages (domain, url, partner_id, type, action, header, footer, page_title, meta_title, meta_description, index_yn, live_yn) VALUES ('www.responsiblelending.co.uk', '/service-for-life', '7', 'Content\\Rlending', 'serviceForLife', 'rlending', 'rlending', 'A service for life', 'Our exceptional customer service', 'Find out about Responsible Lending’s safeguards, guarantees and dedicated team.', '1', '1');` | Creates a "Service for Life" page and updates meta title and description. |
| 8    | `UPDATE responsible_lending_development.site_pages SET meta_title = 'Helpful information for Existing Customers.', meta_description = 'Get information on Drawdowns, repayments, and moving home.' WHERE (id = '105');` | Updates meta title and description for /existing-customers page. |
| 9    | `UPDATE responsible_lending_development.site_pages SET meta_title = 'Helpful resources for existing customers.', meta_description = 'Access our important documents and costs of equity release estimator.' WHERE (id = '320');` | Updating meta title and description for /helpful-resources on the customers page. |
| 10   | `UPDATE responsible_lending_development.site_pages SET url = '/making-a-complaint', page_title = 'Responsible Lending \| Making a complaint', meta_title = 'Making a complaint.', meta_description = 'Who to contact in the event you have a complaint.' WHERE (id = '323');` |I changed an existing page to be the Complaint page, so please check the id of 323 on the prod database, in all likelihood it's a page we are no longer using.         |
| 11    | `UPDATE responsible_lending_development.site_pages SET meta_title = 'Responsible Lending: Offering an exceptional experience.', meta_description = 'Find out more about the equity release lender who is the exclusive provider of the Royal London Equity Release products.' WHERE (id = '109');` | Updating meta title and description for /helpful-resources on the customers page. |


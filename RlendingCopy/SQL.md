# Launching RLife Myths Copy

## PRs (Pull Requests)

- [ ] PR for RLife : [PR #392](https://github.com/responsiblelife/rer-website-futureproof/pull/392)


## SQL Statements and Descriptions

| S.No | SQL Query                                                                                                                                                                                                  | Description                                                                                                                                      |
|------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.   | `INSERT INTO `responsible_lending_development`.`leadgen` (`name`, `template`, `template_results`, `form`, `lead_group_id`) VALUES ('RLife Mythss', 'rlife/landing/v2', 'calculator-results', 'ThreeStepRlifeV2', '60411');`                                 | Creates a new leadgen template named 'RLife Mythss' with the specified template, template results, form, and lead group ID.                   |
| 2.   | `INSERT INTO `responsible_lending_development`.`site_pages` (`domain`, `url`, `partner_id`, `type`, `action`, `page_type_id`, `header`, `footer`, `meta_title`, `live_yn`) VALUES ('equityrelease.responsiblelife.co.uk', '/landing/myths/results', '13', 'Leadgen', 'results', '67', 'rlife', 'rlife', 'Your Results \| Responsible Life', '1');` | Creates the results page for the calculator on the specified domain and URL.                                                                   |
| 3.   | `INSERT INTO responsible_lending_development.site_pages (domain, url, partner_id, type, action, page_type_id, header, footer, meta_title, live_yn) VALUES ('equityrelease.responsiblelife.co.uk', '/landing/myths/results', '13', 'Leadgen', 'results', '67', 'rlife', 'rlife', 'Your Results \| Responsible Life', '1');`                                        | Creates the new landing/myths page and links the page ID to the one created earlier. |

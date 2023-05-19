!!! Tip "NOTE"

     This page is still under construction.

OWASP Juice Shop is an Angular/Node.js based vulnerable web application written by [Björn Kimminich](https://github.com/bkimminich).

### Official Links
* [Website](https://owasp.org/www-project-juice-shop/)
* [Github](https://github.com/juice-shop/juice-shop)
* [Documentation](https://pwning.owasp-juice.shop/)

### Installation
#### Download docker image
```shell
docker pull bkimminich/juice-shop
```

#### Run
```shell
docker run --rm -p 3000:3000 bkimminich/juice-shop
```

#### Start
Browse to [http://localhost:3000](http://localhost:3000)

### Challenges

#### &#9733; Challenges
| Vulnerability category                                                                                        | Description                                                                                                                                                                         | Solution                                                                                                                                                                                                                                       | Difficulty |
|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Miscellaneous                                                                                                 | [&#9099; Score Board](https://pwning.owasp-juice.shop/part2/score-board.html#find-the-carefully-hidden-score-board-page)                                                            | [&#9099; Find the carefully hidden score board](https://pwning.owasp-juice.shop/appendix/solutions.html#find-the-carefully-hidden-score-board-page)                                                                                            | &#9733;    | 
| [&#9099; XSS](https://owasp.org/www-community/attacks/xss)                                                    | [&#9099; DOM XSS](https://pwning.owasp-juice.shop/part2/xss.html#perform-a-dom-xss-attack)                                                                                          | [&#9099; Perform a dom xss attack](https://pwning.owasp-juice.shop/appendix/solutions.html#perform-a-dom-xss-attack)                                                                                                                           | &#9733;    |
| [&#9099; XSS](https://owasp.org/www-community/attacks/xss)                                                    | [&#9099; Bonus Payload](https://pwning.owasp-juice.shop/part2/xss.html#use-the-bonus-payload-in-the-dom-xss-challenge)                                                              | [&#9099; Use the bonus payload in the DOM XSS challenge](https://pwning.owasp-juice.shop/appendix/solutions.html#use-the-bonus-payload-in-the-dom-xss-challenge)                                                                               | &#9733;    |
| Miscellaneous                                                                                                 | [&#9099; Bully Chatbot](https://pwning.owasp-juice.shop/part2/miscellaneous.html#receive-a-coupon-code-from-the-support-chatbot)                                                    | [&#9099; Receive a coupon code from the support chatbot](https://pwning.owasp-juice.shop/appendix/solutions.html#receive-a-coupon-code-from-the-support-chatbot)                                                                               | &#9733;    |
| [&#9099; Sensitive Data Exposure](https://owasp.org/Top10/A02_2021-Cryptographic_Failures/)                   | [&#9099; Confidential Document](https://pwning.owasp-juice.shop/part2/sensitive-data-exposure.html#access-a-confidential-document)                                                  | [&#9099; Access a confidential document](https://pwning.owasp-juice.shop/appendix/solutions.html#access-a-confidential-document)                                                                                                               | &#9733;    |
| [&#9099; Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)              | [&#9099; Error Handling](https://pwning.owasp-juice.shop/part2/security-misconfiguration.html#provoke-an-error-that-is-neither-very-gracefully-nor-consistently-handled)            | [&#9099; Provoke an error that is neither very gracefully nor consistently handled](https://pwning.owasp-juice.shop/appendix/solutions.html#provoke-an-error-that-is-neither-very-gracefully-nor-consistently-handled )                        | &#9733;    |
| [&#9099; Sensitive Data Exposure](https://owasp.org/Top10/A02_2021-Cryptographic_Failures/)                   | [&#9099; Exposed Metrics](https://pwning.owasp-juice.shop/part2/sensitive-data-exposure.html#find-the-endpoint-that-serves-usage-data-to-be-scraped-by-a-popular-monitoring-system) | [&#9099; Find the endpoint that serves usage data to be scraped by a popular monitoring system](https://pwning.owasp-juice.shop/appendix/solutions.html#find-the-endpoint-that-serves-usage-data-to-be-scraped-by-a-popular-monitoring-system) | &#9733;    |
| Miscellaneous                                                                                                 | [&#9099; Mass Dispel](https://pwning.owasp-juice.shop/part2/miscellaneous.html#close-multiple-challenge-solved-notifications-in-one-go)                                             | [&#9099; Close multiple "Challenge solved"-notifications in one go.](https://pwning.owasp-juice.shop/appendix/solutions.html#close-multiple-challenge-solved-notifications-in-one-go)                                                          | &#9733;    |
| [&#9099; Improper Input Validation](https://owasp.org/www-community/vulnerabilities/Improper_Data_Validation) | [&#9099; Missing Encoding](https://pwning.owasp-juice.shop/part2/improper-input-validation.html#retrieve-the-photo-of-bjoerns-cat-in-melee-combat-mode)                             | [&#9099; Retrieve the photo of Bjoern's cat in "melee combat-mode".](https://pwning.owasp-juice.shop/appendix/solutions.html#retrieve-the-photo-of-bjoerns-cat-in-melee-combat-mode)                                                           | &#9733;    |
| Unvalidated Redirects                                                                                         | [&#9099; Outdated Allowlist](https://example.com)                                                                                                                                   | [&#9099; XXXX](https://example.com)                                                                                                                                                                                                            | &#9733;    |
| Miscellaneous                                                                                                 | [&#9099; Privacy Policy ](https://example.com)                                                                                                                                      | [&#9099; XXXX](https://example.com)                                                                                                                                                                                                            | &#9733;    |
| Improper Input Validation                                                                                     | [&#9099; Repetitive Registration](https://example.com)                                                                                                                              | [&#9099; XXXX](https://example.com)                                                                                                                                                                                                            | &#9733;    |
| Improper Input Validation                                                                                     | [&#9099; Zero Stars](https://example.com)                                                                                                                                           | [&#9099; XXXX](https://example.com)                                                                                                                                                                                                            | &#9733;    |

#### &#9733;&#9733; Challenges
coming soon

#### &#9733;&#9733;&#9733; Challenges
coming soon

#### &#9733;&#9733;&#9733;&#9733; Challenges
coming soon

#### &#9733;&#9733;&#9733;&#9733;&#9733; Challenges
coming soon

#### &#9733;&#9733;&#9733;&#9733;&#9733;&#9733; Challenges
coming soon
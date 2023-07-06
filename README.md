# AWS IP Prefixes Search Page

This repository hosts a simple, user-friendly search interface for Amazon Web Services (AWS) IP prefixes. You can access the live site [here][(https://ebrahimahmadi.github.io/aws-ip-ranges-html-search/)].

## Use Cases

This search interface can be useful in a number of situations:

1. **Security:** Security administrators can use this page to quickly find the IP ranges associated with specific AWS services or regions. This can help with setting up firewall rules that only allow traffic from trusted AWS services.

2. **Network Configuration:** If a company uses AWS and wants to ensure that its internal systems only accept traffic from AWS, they can use this interface to find the appropriate IP ranges.

3. **Traffic Analysis:** Network analysts can use this page to identify network traffic associated with AWS services.

4. **Troubleshooting:** Developers and system administrators can use this page to investigate whether changes in AWS IP ranges have impacted application behavior.

## How It Works

This page fetches a JSON feed of AWS IP prefixes and provides a simple interface to search this data. You can filter results by IP prefix, region, service, and network border group. The page uses basic HTML, CSS, and JavaScript and is hosted using [GitHub Pages](https://pages.github.com/).

Please note: This page is publicly accessible, so do not include any sensitive information in your searches. Also, be aware of CORS (Cross-Origin Resource Sharing) issues if the JSON feed is hosted on a different domain. The server hosting the JSON feed needs to include the appropriate CORS headers for the fetch request to work.

## License

This project is open source and available under the [MIT License](LICENSE).

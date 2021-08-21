
Curated list of useful links, tools and resources for Web development and DNS

You can also view it in [my website](https://www.kappawingman.com/useful-links/).
It is another way for presenting the information.

Cloud Computing and Cloud-native
--------------------------------

- Cloud service providers
  - AWS
    - [AWS Service Health Dashboard](https://status.aws.amazon.com)
    - [Personal Health Dashboard](https://phd.aws.amazon.com)
  - Azure
    - [Azure Status Dashboard, Primary](https://status.azure.com)
    - [Azure Status Dashboard, Secondary](https://status2.azure.com)
  - GCP
    - [Google Cloud Status Dashboard](https://status.cloud.google.com)
  - Cloudflare
    - [Cloudflare System Status](https://www.cloudflarestatus.com)
  - IBM Cloud
    - [IBM Cloud Status Dashboard](https://cloud.ibm.com/status)
  - Oracle Cloud
    - [OCI Status Dashboard](https://ocistatus.oraclecloud.com)
  - Akamai
    - [Akamai System Status](https://edgedns.status.akamai.com)
- CI/CD
  - CI/CD Service providers
    - [GitHub Status](https://www.githubstatus.com)
    - [GitLab System Status](https://status.gitlab.com)
    - [CircleCI Status](https://status.circleci.com)
- Service Mesh
  - [Comparison of service meshes by InnoQ](https://servicemesh.es/)

Web development
---------------

- Website performance, SEO and security (online tools)
  - [WebPageTest](https://www.webpagetest.org) - Their waterfall graph and connection graph is useful for 
optimizing your loading speed
  - [Techinical SEO](https://technicalseo.com/tools) - This site has several tools for SEO
  - [Freeformatter](https://www.freeformatter.com/) - This site has formatters, validators, encoders, decoders minifiers and converters
  - [KeyCDN](https://tools.keycdn.com/) - Several tools provided, website speed test and other network tools
  - [Uptrends](https://www.uptrends.com/tools) - Website, CDN speed test and other tools
  - [Pingdom](https://tools.pingdom.com) - Website speed test
  - Scanning
    - [Dareboost](https://www.dareboost.com) - Provides recommendation
    - [Nibbler](https://nibbler.silktide.com) - Provides recommendation, free version only scan maximum of five links automatically from your website
    - [Lighthouse Metrics](https://lighthouse-metrics.com) - Website that performs Google Lighthouse checking in browser
    - [Google Pagespeed Insights](https://developers.google.com/speed/pagespeed/insights/)
    - [Mobile friendly checking by Google](https://search.google.com/test/mobile-friendly)
    - [A project using Server-Daten](https://check-your-website.server-daten.de) **Scan and check a LOT of things including HTTPS, cookies, CSP, DNS, port checking and etc. It would took minutes. Use with caution**
    - HTTP/3
      - [HTTP3check.net by LiteSpeed Tech](https://http3check.net) - Check if a website support HTTP/3
      - [Check if your browser support HTTP/3](https://cloudflare-quic.com/) - By Cloudflare
    - Cloudflare
      - [Check your browser connection to Cloudflare](https://www.cloudflare.com/cdn-cgi/trace) - Display your IP, WARP status and etc.
    - Security focused
      - [Mozilla Observatory](https://observatory.mozilla.org/) - Combines several third party scanning tools and display it. **Recommended**
      - [Immuniweb Community Free Security Tests](https://www.immuniweb.com/free/) - Free web/domain/SSL scan
      - [Sucuri](https://sitecheck.sucuri.net/) - Free website security check & malware scanner
      - [Website and E-mail scanning](https://internet.nl/) - Initative of the Internet Community and the Dutch government
    - Scanning HTTP headers and CSP
      - [Webbkoll](https://webbkoll.dataskydd.net/en) - Checking CSP with detail explanation about GDPR and settings. Also support self-hosting. **Recommended**
      - [Security Headers Sponsored by Report URI](https://securityheaders.com/)
      - [Analyse CSP by report-uri](https://report-uri.com/home/analyse)
      - [CSP Evaluator by Google](https://csp-evaluator.withgoogle.com/)
      - [Redbot](https://redbot.org)
      - [Gift of Speed](https://www.giftofspeed.com/cache-checker/) - Display a list about the maximum cache age of the webpage, also have other tools in that website
      - [Test CORS](https://www.test-cors.org) - You should open browser developer tools when testing against an URL for CORS
      - [Check if your Chrome browser is FLOCED](https://amifloced.org/)
    - Cookies
      - [Webcookies](https://webcookies.org/) - Scan what cookies are used and give recommendation
    - Find out what technologies are used in a website
      - [Builtwith](https://builtwith.com/)
      - [W3techs](https://w3techs.com/sites)
- JSON-LD
  - Verification
    - [Visualisation of strucuted data by Classy Schema](https://classyschema.org/Visualisation) **- Recommended**
    - [Rich Results Test with Rich Snippet Preview](https://search.google.com/test/rich-results) **- Recommended, by Google**
    - [Schema Validator](https://validator.schema.org/) - Replaced an old Google online tool
    - [Structured Data Linter](http://linter.structured-data.org) - HTTPS of this website does not work correctly, browser giving out warning about hostname problem 
  - Generator
    - [By Technical SEO](https://technicalseo.com/tools/schema-markup-generator/)
    - [By Google](https://www.google.com/webmasters/markup-helper/)
    - [By jsonld.com](https://jsonld.com/json-ld-generator/)
- Robots.txt
  - Validator
    - [By Google](https://www.google.com/webmasters/tools/robots-testing-tool)
    - [Tester by Techincal SEO](https://technicalseo.com/tools/robots-txt/)
    - [Robots Meta Directives by Moz](https://moz.com/learn/seo/robots-meta-directives)
- Monitoring and Reporting
  - Security and Error reporting
    - [Sentry](https://sentry.io/) - Have free plan suitable for dev or small website. Also support self hosting but not reselling it (BSL license)
    - [Report-URI](https://report-uri.com/) - Have free plan suitable for dev or small website
- Page preview
    - [Metatags.io](https://metatags.io/) - Preview how a webpage look like in Google Search, Facebook, Twitter, Linkedin, Pinterest and Slack
- Google, some tools are usable but not displayed in the search console by default
    - [Search Console](https://search.google.com/u/0/search-console/welcome)
    - [Remove outdated content (owner)](https://www.google.com/webmasters/tools/removals)
    - [Remove outdated content (non-owner)](https://search.google.com/search-console/remove-outdated-content)
    - [URL parameters](https://www.google.com/webmasters/tools/crawl-url-parameters)
- PWA
  - [PWABuilder](https://www.pwabuilder.com)
- HTML
  - Validator
    - [W3C Markup Validation Service](https://validator.w3.org/) - An online tool
    - [html5validator, written in Python](https://github.com/svenkreiss/html5validator) - Command line tool
    - [CSS Validator](https://jigsaw.w3.org/css-validator/) - An online tool
  - [Can I Use](https://caniuse.com/) - Browser support table for modern web technologies
 - Front-end playground for testing code or demo
   - [Codepen](https://codepen.io/)
   - [JSFiddle](https://jsfiddle.net/)
   - [CodeSandBox](https://codesandbox.io/)
- CDN
  - [jsDelivr](https://www.jsdelivr.com/)
  - [cdnjs](https://cdnjs.com/)
  - [Skypack](https://www.skypack.dev/)
  - [unpkg](https://unpkg.com/)
  - [ESM.sh](https://esm.sh/)
- Web PKI
  - Certificate Transparency
    - [Check CT database By Google](https://transparencyreport.google.com/https/certificates) - Online tool
    - [Censys.io](https://search.censys.io) - Online tool for checking hostname or certificates history
    - [Online utility to check if the web server is returning correct certificate chains](https://www.digicert.com/help/) - By DigiCert
  - [Check the TLS settings supported by your browser by SSLLabs](https://clienttest.ssllabs.com:8443/ssltest/viewMyClient.html)
- JavaScript
  - [Browser support matrix of ES6+](https://kangax.github.io/compat-table/es2016plus/)

DNS
---

- Online tools
  - Check DNS records from a specific DNS
    - [Network-tools.com](https://network-tools.com/nslookup/)
  - Troubleshooting DNSSEC
    - [DNSSEC Analyzer by Versign Labs](https://dnssec-debugger.verisignlabs.com/)
    - [DNSViz](https://dnsviz.net/)
  - WHOIS
    - [ICANN Whois](https://lookup.icann.org/lookup)
    - [Versign Whois](https://www.verisign.com/en_GB/domain-names/whois/index.xhtml?loc=en_GB) - Cloudflare said ICANN is cached and may have delay, and Versign should be used instead. But this Whois server does not support all TLDs
- Flushing public DNS cache of some vendors
  - [Cloudflare](https://1.1.1.1/purge-cache/)
  - [Google](https://developers.google.com/speed/public-dns/cache)

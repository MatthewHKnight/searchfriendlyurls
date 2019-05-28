# searchfriendlyurls
This is a rip of Searchfriendlyurls.com fully functional.
Enter ugly and pretty URLs in the space provided to generate search friendly redirects for your server.

URLs should not begin with domain names or slashes, and servers must support rewrite rules.

For dynamic URLs, place the dynamic parts inside < and >.

For VPS or Dedicated server Apache2 must be installed.
Command: sudo a2enmod rewrite
needs to be run in a Linux terminal, to allow a site to work.
This only needs to be run on a VPS or Dedicated server shared hosting will likely are have it enabled.

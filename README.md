# Tesla public-key hosting

Publish the included `.well-known/appspecific/com.tesla.3p.public-key.pem` at the root of the public HTTPS domain entered in Tollwise. Only this public PEM may be uploaded. The private key and client secret remain in the ignored local data folder.

For GitHub Pages using Jekyll, add a `.nojekyll` file at the site root so `.well-known` is published. Verify the exact HTTPS file URL returns the PEM directly (200), then register the region from local Tollwise.

This bundle contains no private key, token, client secret, or driving records.

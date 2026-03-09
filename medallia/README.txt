This package contains the Medallia Digital Dynamic survey package. Once deployed any changes made to the surveys and its configuration will be reflected automatically on your website.

In case a previous package has already been deployed, please make sure to unpack this package to the same location or update all references to the location of the unpacked package.

Steps required for deploying the digital package:

1. Unpack the zip file to the deployment directory.
2. Make sure that the deployment directory is accessible for public connections.
3. Add the following code to your website (preferably at the end of the HTML body section). Make sure that you replace directory with URL path.

<script type=“text/javascript” src=“<path to package>/wdceu/779006/onsite/medallia-digital-embed.js>“></script>

Important:
In case that your package is deployed on a server which is not on the same domain where you embed Medallia Digital, Please add the following script BEFORE the embed tag.

<script> MDIGITAL_ON_PREM_PREFIX = <path to package> </script>

For additional support please reach out to your Digital Expert or open a ticket at https://help.medallia.com

Copyright (c) 2020 Medallia Inc. All rights reserved.
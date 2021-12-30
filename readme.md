[comment]: # " File: readme.md"
[comment]: # ""
[comment]: # "  Copyright (c) 2020-2021 Splunk Inc."
[comment]: # ""
[comment]: # "  Licensed under the Apache License, Version 2.0 (the \"License\");"
[comment]: # "  you may not use this file except in compliance with the License."
[comment]: # "  You may obtain a copy of the License at"
[comment]: # ""
[comment]: # "      http://www.apache.org/licenses/LICENSE-2.0"
[comment]: # ""
[comment]: # "  Unless required by applicable law or agreed to in writing, software distributed under"
[comment]: # "  the License is distributed on an \"AS IS\" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,"
[comment]: # "  either express or implied. See the License for the specific language governing permissions"
[comment]: # "  and limitations under the License."
[comment]: # ""
## Licensing details for the app

### hvac

This app uses the hvac module, which is licensed under the Apache Software License, Copyright (c)
Ian Unruh, Jeffrey Hogan.

### six

This app uses the six module, which is licensed under the MIT License (MIT), Copyright (c) Benjamin
Peterson.

**Port Information**
*  The app uses HTTP/ HTTPS protocol for communicating with the Hashicorp Vault server. Below are the default ports used by the Splunk SOAR Connector.

    SERVICE NAME | TRANSPORT PROTOCOL | PORT
    ------------ | ------------------ | ----
    http | tcp | 80
    https | tcp | 443

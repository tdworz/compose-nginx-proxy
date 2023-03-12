Compose: nginx-docker
=====================

This project is a [compose spec](https://compose-spec.io/) setup for
[nginx-proxy](https://github.com/nginx-proxy/nginx-proxy).


Example `.env`
--------------

Most configuration may be done by including a `.env` file in the same directory
as the `compose.yml` file. The following is an example of the contents of a
`.env` file.

```yaml
IMAGE_VARIANT=alpine
TLS_DIRECTORY_PATH=/srv/tls
SSL_POLICY=Mozilla-Modern
DEFAULT_HOST=example.com
RESTART_POLICY=unless-stopped
NETWORK_NAME=edge
```


Copyright & License
-------------------

Copyright ©2023 Tom Dworzanski (tdworz)

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, please see https://www.gnu.org/licenses/gpl-3.0.en.html.

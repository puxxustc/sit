# sit #

Userspace sit(IPv6 over IPv4) tunnel, designed for OpenVZ servers (require TUN device support).

## Build ##

```bash
gcc -std=gnu99 -O2 -pipe -o sit sit.c
```

## Usage ##

```bash
sudo ./sit <tun dev> remote local
```

## License ##

Copyright (C) 2015, Xiaoxiao <i@xiaoxiao.im>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

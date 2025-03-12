ZBX-ejabberd
==============

This template uses the zabbix agent to monitoring ejabberd server.


Items
-----

  * ejabber outgoing_s2s_number
  * ejabber outgoing_s2s_number
  * ejabber outgoing_s2s_number
  * xmpp-server service is running
  * xmpp-client service is running

Triggers
--------
  * xmpp-client port is listened.

Graphs
------

  * ejabberd connection status

Installation
------------

1. Import **zbx-ejabberd-template.xml** file into Zabbix.
2. Add **ejabberd.conf** to zabbix agentd config on your jabber host and add **zabbix** to sudo. Check: ``visudo -sc``

3. Associate **Template App Ejabberd** template to the host.

### Requirements

This template was tested to work with Zabbix 2.2.0 up to 5.0.xx. **sudo** is required to get statistics from ejabberd daemon.

### Copyright

  Copyright (c) 2016-2025 Igor Popov

License
-------
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

### Authors

  Igor Popov
  (ipopovi |at| gmail |dot| com)

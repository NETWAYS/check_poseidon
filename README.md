check_poseidon
==============

Checks the HW group Poseidon devices.

http://shop.netways.de/ueberwachung/hersteller/hw-group.html

### Usage

    check_poseidon.pl -h

    check_poseidon.pl -H <host> ( -S <sensor id> | -I <input id> | -O
    <output id> )

Options:

    -h      Display this helpmessage.
    -H      The hostname or ipaddress of the hwgroup device.
    -C      The snmp community of the hwgroup device.
    -S      The sensor to check
    -I      The dry contact to check
    -O      The relay output to check
    --man   Displays the complete perldoc manpage.


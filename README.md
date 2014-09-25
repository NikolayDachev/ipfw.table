IPFW Table from file:

Add ip addresses from file to ipfw table:

usage:

    ipfw.table 'table number' '/ip/file/path'

example:

    ipfw.table 1 /etc/ipfw.deny

    1 - tbale number
    /etc/ipfw.deny - file with ip addresses

   file should content one ip address per line (only ip address - no subnet)

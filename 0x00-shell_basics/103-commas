#!/bin/bash
ls -ap1 | awk '{ if ($0 == "./" || $0 == "../") { print $0 } else if (substr($0, 1, 1) == ".") { printf "%s,", $0 } else { printf "%s/,", $0 } } END { printf "\n" }'

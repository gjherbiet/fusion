# fusion

A VMWare Fusion headless launcher.

## Usage

    fusion [-h|--help] [-V|--version] [-D|--debug] [-v|--verbose] [-N|--dry-run]
        [-l|--location] [-c|--command] [-g|--gui] VM_NAME

      Launches VM_NAME in VMWare Fusion in headless mode from the command line.

      Note: If your system has the non-enhanced version of 'getopt' (which is the
      case by default on BSD systems, including Mac OS), only the short version
      of the following options are available.

        --help, -h       : Print this help, then exit.
        --version, -V    : Print the software version, then exit.
        --debug, -D      : Extended information about the script function.
        --verbose, -v    : Display a summary of the executed operations.
        --dry-run, -N    : Do not perform any actual action

        --location, -l   : Virtual machine location
                           (default: /Users/<USERNAME>/Documents/Virtual Machines.localized)
        --command, -c    : Command used to launch the virtual machine
                           (default: /Applications/VMware Fusion.app/Contents/Library/vmrun -T fusion start)
        -gui, -g         : Use user interface (i.e. not headless mode)


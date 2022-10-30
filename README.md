# bonsai [![Build Status](https://travis-ci.com/mitchweaver/bonsai.svg?branch=master)](https://travis-ci.com/mitchweaver/bonsai)

```
# -/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/- #
#                                                         #
#                   ,####,                                #
#                   #######,  ,#####,                     #
#                   #####',#  '######                     #
#                   ''###'';,,,'###'                      #
#                          ,;  ''''                       #
#                         ;;;   ,#####,                   #
#                        ;;;'  ,,;;;###                   #
#                        ';;;;'''####'                    #
#                         ;;;                             #
#                      ,.;;';'',,,                        #
#               #     '     '                             #
#               #                        O                #
#               ##, ,##,',##, ,##  ,#,   ,                #
#               # # #  # #''# #,,  # #   #                #
#               '#' '##' #  #  ,,# '##;, #                #
#                                                         #
#                                                         #
#          http://github.com/mitchweaver/bonsai           #
#                                                         #
#                      * NOTICE *                         #
#                                                         #
#       In early development. Not intended for use.       #
#                                                         #
# -/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/-/- #
```

## Bonsai

Originally the package manager of a now extinct hobby Linux distribution,
`bonsai` is small package manager meant to be cross-platform and extremely
simple to use. Written in POSIX shell with only basic UNIX utilities
as dependencies, it's meant to be able to be pulled down on any machine
to quickly get access to the programs you need, root access not required.

As of now I am personally using it for miscellaneous things not commonly
found in the distros I use. As I get time it will get fleshed out as a
serious project.

Maybe it will be of use to you too.  
Feel free to open github issues/PR as needed.

\- Mitch

---

## Installation

```
git clone https://github.com/mitchweaver/bonsai
cd bonsai
make
make install
```

## Environment

```
cat >> ~/.profile <<EOF
if [ -d ~/.bonsai ] ; then
    export PATH="${HOME}/.bonsai/bin:$PATH"
    export MANPATH="${HOME}/.bonsai/share/man:$MANPATH"
fi
EOF
```

## Usage

```
bs -h
```

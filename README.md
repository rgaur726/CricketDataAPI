# API for cricket information generation

This Python libary provides an api for accessing information from CricInfo like live scores, news updates and player profiles.

## Usage

    # instantiate
    matches = CricInfo()
    # iterate though matches
    for match in matches:
        print match.title
        print match.description
        print match.link
        print match.guid

Simple as that !

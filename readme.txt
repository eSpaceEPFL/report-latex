eSpace Latex Report Template

    Provides a latex template with eSpace document style guidelines

    All figures should be stored in fig folder

    Uses Biber for bibliography. For TeXLive users, add Biber compiler with
        program: biber
        arguments: $basename
    Separation between type of bibliography documents is done at the file level.

Special and useful functions

    \figi{filename}{fig:label}{text to display}{width}
        Places a figure at the exact place in on line

    \unit{m/kg}
        Guarantees correct unit display style. Only available in math mode
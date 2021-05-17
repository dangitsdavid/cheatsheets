# vim-cheatsheet
A cheatsheet for VIM cause its cool

## Content:
1. [Basic Commands](https://github.com/dangitsdavid/cheatsheets/blob/main/vim-cheatsheet.md#basic-commands)
2. [Navigation Commands](https://github.com/dangitsdavid/cheatsheets/blob/main/vim-cheatsheet.md#navigation-commands)
3. [Search Commands](https://github.com/dangitsdavid/cheatsheets/blob/main/vim-cheatsheet.md#search-commands)
4. [Edit Commands](https://github.com/dangitsdavid/cheatsheets/blob/main/vim-cheatsheet.md#edit-commands)
5. [Exit Commands](https://github.com/dangitsdavid/cheatsheets/blob/main/vim-cheatsheet.md#exit-commands)

## Basic Commands [top]()
| Command       | Action                                |
| ------------- | -------------                         |
| [esc]         | Exit out of mode                      |
| i             | Insert text                           |
| I             | Type at the beginning of the line     |
| a             | Type after the cursor                 |
| A             | Type at the end of line               |
| o             | Type on a new line before cursor      |
| O             | Type on a new line after cursor       |

## Navigation Commands
| Command       | Action                                |
| ------------- | -------------                         |
| gg            | Move to beginning of file             |
| G             | Move to end of file                   |
| $             | Move to the end of the same line      |
| 0             | Move to beginning of same line        |
| }             | Move to next space of a paragraph     |
| {             | Move to previous space of a paragraph |
| j or k        | Move up (**j**) and down (**k**)      |
| w             | Move to next word                     |
| W             | Move to next work separated by space  |
| v             | Move to the previous word             |
| V             | Move to the previous word separated by space |

## Search Commands
| Command       | Action                                       |
| ------------- | -------------                                |
| f             | Looks for an input character to the right    |
| F             | Looks for a character to the left            |
| /             | Search for text                              |
| n             | Continue search in right direction           |
| N             | Continue search in left direction            |
| #             | Search for the same word that cursor is on - right direction  |
| #             | Search for the same word that cursor is on - left direction   |

## Edit Commands
| Command       | Action                                       |
| ------------- | -------------                                |
| u             | Reverse action                               |
| d + }         | Delete entire line that cursor is on.        |
| d + f + )     | Delete row until closing character )         |
| d + t + )     | Delete row before closing chacter )          |
| d + w         | Delete one word                              |
| 2 + d + w     | Delete two words                             |
| 3 + d + w     | Delete three words                           |
| d + d         | Delete entire line                           |
| p             | Paste deleted line on line after cursor      |
| P             | Paste deleted line on line before cursor     |
| d + i + t     | Delete characters inside a <tag> </tag>      |
| d + a + t     | Delete entire <tag> </tag>                   |
| c + i + t     | Delete characters inside a <tag> </tag> and enter insert mode   |
| d + i + (     | Delete characters inside a ( parenthesis )   |
| d + a + (     | Delete entire ( parenthesis )                |
| c + i + (     | Delete characters inside a ( parenthesis ) and enter insert mode   |

## Exit Commands
| Command       | Action                                       |
| ------------- | -------------                                |
| : + w         | Save changes to file                         |
| : + w + <filename>  | Save changes to new file <filename>    |
| : + x         | Save changes and exit                        |
| : + q         | Quit Vim (no changes made)                   |
| : + q + !     | Quit Vim (don't save changes)                |

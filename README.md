# works-sprig

  - [What's this](#whats-this)
    - [Concept Movie](#concept-movie)
    - [Demo](#demo)
  - [How to Use](#how-to-use)
    - [Tutorial Movie](#tutorial-movie)

__Now implementing...__

- [x] Keyboard-oriented mode
- [ ] Touch-oriented mode

<!-- EXTERNAL LINK -->
[Concept]: https://youtu.be/4MatFmieAwE
<!-- TODOX [Demo1]: https://demo.sprig.work/ -->
[Demo2]: https://satu-n.github.io/works-sprig/
[Docker]: https://docs.docker.com/get-docker/
[SendGrid]: https://sendgrid.com/
[SparkPost]: https://sparkpost.com/
[Tips]: https://github.com/satu-n/tips
[Tutorial]: https://youtu.be/PhxihW87N74

<!-- INTERNAL LINK -->
[Network Diagram]: etc/network_diagram.jpg
[Placeholder]: web/src/Page/App/Placeholder.elm
[Screen]: etc/screen_description.jpg
[Screen-ja]: etc/screen_description-ja.jpg

<!-- TODOX ![Network Diagram][Network Diagram] -->

## What's this

___Sprig___, the Task Breaker ⚡

![Screen Description][Screen]

![Screen Description in Japanese][Screen-ja]

### [Concept Movie][Concept]

### Zen of Sprig

* ___List up, and enter as is.___
* ___Break it down into processable units.___
* ___Focus on the top task.___

### [Demo][Demo1]

* A random username and the same password will be issued.
* Click username to logout to create another account.
* Data may be deleted without notice.

1. [Demo on Amazon ECS, recommended][Demo1]
2. [Demo on GitHub Pages & Heroku][Demo2]
   * The response may be delayed, because the API server will sleep if there is no access for a while.

## How to Use

### [Tutorial Movie][Tutorial]

### Input Syntax

See input area [Placeholder][Placeholder].

### Shortcuts

|                             Icon                              |           Shortcut | Operation                                         |
| :-----------------------------------------------------------: | -----------------: | ------------------------------------------------- |
|                                                               |                    | __INPUT__                                         |
|                                                               |                `/` | focus input area                                  |
|                                                               |         `Ctrl` `↓` | maximize input area                               |
|                                                               |              `Tab` | indent                                            |
|                                                               |      `Shift` `Tab` | unindent                                          |
|                                                               |     `Ctrl` `Enter` | send                                            |
|                                                               |         `Ctrl` `↑` | minimize input area                               |
|                                                               |              `Esc` | blur input area                                   |
|                                                               |                    | __NAVIGATE__                                      |
| <img src="web/images/cmd_jk.png" width="24px" align="center"> |         `J` \| `K` | down & up cursor                                  |
| <img src="web/images/cmd_x.png" width="24px" align="center">  |                `X` | select item at cursor                             |
| <img src="web/images/cmd_u.png" width="24px" align="center">  |                `U` | open URL of item at cursor in new tab             |
| <img src="web/images/cmd_i.png" width="24px" align="center">  |                `I` | Invert selection                                  |
|                                                               |                    | __EDIT__                                          |
| <img src="web/images/cmd_s.png" width="24px" align="center">  |                `S` | Star item at cursor                               |
| <img src="web/images/cmd_e.png" width="24px" align="center">  |                `E` | Execute selected items to archives                |
| <img src="web/images/cmd_e.png" width="24px" align="center">  | `V` \| `Shift` `E` | reVert selected items to home                     |
| <img src="web/images/cmd_c.png" width="24px" align="center">  |                `C` | Clone selected items to input area                |
|                                                               |                    | __VIEW__                                          |
| <img src="web/images/cmd_qp.png" width="24px" align="center"> |         `Q` \| `P` | time scale                                        |
| <img src="web/images/cmd_wo.png" width="24px" align="center"> |         `W` \| `O` | time shift                                        |
| <img src="web/images/cmd_f.png" width="24px" align="center">  |                `F` | Focus item at cursor: view directly related items |
| <img src="web/images/cmd_a.png" width="24px" align="center">  |                `A` | Archives                                          |
| <img src="web/images/cmd_r.png" width="24px" align="center">  |                `R` | Roots: items with no successor                    |
| <img src="web/images/cmd_l.png" width="24px" align="center">  |                `L` | Leaves: items with no predecessor                 |
| <img src="web/images/cmd_h.png" width="24px" align="center">  |                `H` | Home                                              |

### Logout

Click username.

## Thank you for reading !

See also [My Dev Tips][Tips] if you like.
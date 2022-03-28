# Fast F#

This is a book under development on how to write fast F# code. The books website can be found [here](https://fastfsharp.com). I welcome contribution in the form of Case Study chapters or theory chapters where you go into detail on how F# works and the performance implications.

## Building Locally

The book is built using Hugo and utilizes the [Hugo Book](https://github.com/alex-shpak/hugo-book#installation) theme. If you want to edit locally, I recommend cloning this repo then cloning the theme using a git submodule.

> **Note:** You will need to have a version of Hugo which meets the requirements of the theme

1. Clone this repo locally
2. Open a terminal in the cloned repo
3. Clone the theme using `git submodule add https://github.com/alex-shpak/hugo-book themes/hugo-book`
4. Run the hugo server locally using `hugo server --minify --theme hugo-book`


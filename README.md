# .dotfiles

A collection of my dotfiles.

## Stow

I use [GNU Stow](https://www.gnu.org/software/stow/) to organise my dotfiles. This is a prgram that automatically creates symlinkes to the relevent files. If you prefer an aproach without a depedency on 3rd party software, you could look into git bare repo ans setting an external work tree. (This ofcourse still relies on git).

To move the items into the `.config/` folder, use the following command:

```bash
stow --dotfiles dot-cofig -t ~/.config
```

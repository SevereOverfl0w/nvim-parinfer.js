#0.1.3
- Bump neovim-client version. 
- IMPORTANT you need to `cd ~/.config/nvim/bundle/node-host && npm upgrade` to fix a bug in the plugin host that caused the parinfer to crash (should use `neovim-client 1.0.6` dependency)

#0.1.2
- Run paren-mode format on initial buffer load; stops badly formatted files from getting munged 

#0.1.1
- Significant speedup with proper diff algorithm 
- Point to node-host crash fix in README

#0.1.0
- First release

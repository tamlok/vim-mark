# Mark for Vim
Clone Mark from http://www.vim.org/scripts/script.php?script_id=2666.

Highlight several words in different colors simultaneously.

# Key Mappings
- `[N]<leader>hs` to mark the word under the cursor. The next free highlight group is used. If already on a mark, then clear the mark. With `[N]`, mark the word under the cursor with the named highlight group `[N]`.
- `[N]<leader>hr` to manually input a regular expression to mark.
- `[N]<leader>hc` to clear the mark under the cursor. If not on a mark, then disable all the marks.

## Notes and code snippets so I dont forget
#### To-Do
- [ ] delete broken files
- [ ] change the original index to .24
- [ ] add links
  - [ ] and fix broken
- [ ] add icons
- [ ] figure out wtf with css
    - [ ] try web html export


#### Sidebar content
`<div class="tree-item-contents nav-folder-title"> `

`<div class="block-language-progressbar" ` **or** `<div class="tree-item-contents nav-file-title"` **plus**
```html 
    style="
    display: flex>
```
idk how it works without the secong ", but it doesn't work ***with*** it. 


#### Images
##### 1st
```HTML
<div class="tree-item mod-tree-file nav-file" data-depth="1">
    <a class="tree-link" href="used_links1737997853023.html">
        <div class="tree-item-contents nav-file-title">
            <div class="tree-item-icon">
                <img src ="img/1 (3).jpg"
                    class="svg-icon lucide-file"
                    stroke-linejoin="round"
                    stroke-linecap="round"
                    stroke-width="2"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                    height="24"
                    width="24"
                    xmlns="http://www.w3.org/2000/svg">
                <path 
    d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z">
                </path>
                <polyline points="14 2 14 8 20 8"></polyline>
            </div>
                <span
                class="tree-item-title nav-file-title-content tree-item-inner"
                >used_links1737997853023</span>
        </div>
    </a>
</div>
```

##### 2nd - icons

```HTML
<div class="tree-item mod-tree-file nav-file" data-depth="1">
    <a class="tree-link" href="used_links1737997853023.html">
        <div class="tree-item-contents nav-file-title">
            <div class="tree-item-icon">
                <img src ="img/1 (3).jpg"
                viewBox="0 0 24 24"
                height="24"
                width="24"
                xmlns="http://www.w3.org/2000/svg">
            </div>
                <span
                class="tree-item-title nav-file-title-content tree-item-inner"
                >used_links1737997853023</span>
            </div>
    </a>
</div>
```

##### the final

```html
<div class="tree-item mod-tree-file nav-file" data-depth="1">
    <a class="tree-link" href="used_links1737997853023.html">
        <div class="block-language-progressbar">
            <img src ="img/1 (3).jpg"
                viewBox="0 0 250 250"
                height= 100%
                width= 100%
            >
        </div>
    </a>
</div>
```
# The purpose of this repository is to learn about Markdown.

## This is a header level 2
### This is a header level 3
#### This is a header level 4
##### This is a header level 5
###### This is a header level 6

### Note :
- There are only 6 levels for headers

### Images :
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
![Image of a magic ball](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQx7xcPPdVMIArPHp1h44qGPE2ggEiozAMmfQ&usqp=CAU)

![Image of a pinky little bricks background](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRYqTFgl_bfXfH1iQZwsunbFgxa0B54b6usg&usqp=CAU)

### Adding some Code:
This is a Node.js routing sample
```
let myobj = {}
app.get('/api', (req, res) => {
  myobj['unix']  = new Date().getTime();
  myobj['utc']  = new Date().toUTCString();
  res.json(myobj);
```
### Adding Checkboxes:
- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

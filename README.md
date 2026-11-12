# meshview.github.io

The website of [Meshview](https://github.com/meshview/meshview), served at
<https://meshview.github.io>.

Plain HTML and one stylesheet, `meshview.css`, with nothing to build: GitHub
Pages serves this repository's `master` branch as it stands, and `.nojekyll`
keeps Jekyll from processing it. It is made of Meshview's own pieces, its
header bar, cards and colours, with the same Inter typeface (`fonts/`, SIL Open
Font License) and Tabler icons (`icons/`, MIT) the interface carries. The flags
in the footer are SVG in `flags/`, as emoji flags do not show on Windows. The English page is `index.html` and the
Spanish one `es/index.html`; they say the same, and a change to one goes to the
other.

The screenshots in `shots/` are WebP, 1600×900: the English ones from the San
Francisco Bay Area Mesh, the Spanish ones from O Zulo's mesh. `og.png` is the
image a link to the site shows where it is pasted, 1200×630.
`og-instance.png`, the same size, is the one a link to a Meshview instance
shows when the instance has no `domain` configured to serve its own from: the
same picture Meshview carries, its mark and name with no words that might not
fit the instance. `og-instance-node.png` is its picture for a link to a node:
the mark of a node above Meshview's.

To look at it before publishing:

```sh
python3 -m http.server 8000
```

Free software, under the GNU Affero General Public License, version 3 or later,
as Meshview is.

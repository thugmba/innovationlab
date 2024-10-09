---
title: 'Link Zotero and Obsidian'
date: 2024-10-09
permalink: 
tags:
  - Zotero
  - Obsidian
  - Citation
---

### How to link Zotero and Obsidian



How to cite data in Zotero in Obsidian.
### Install

1. Install [Better BibTeX forZotero](https://retorque.re/zotero-better-bibtex/installation/) plugin in Zotero
2. Install Zotero Integration, Pandoc Reference List plugins in Obsidian
### Configuration

1. In the Zotero Integration's General Settings, add a citation style you want and set the __Output Format__ to __Pandoc__. 
![[Pasted image 20241008162336.png]]
2. In Pandoc Reference List's option, 
  1. Enable __Pull bibliography from Zotero__.
![[Pasted image 20241008162547.png]]

  2. In __Citation style__, choose style you want. In this example, we choose APA 7 edition.
![[Pasted image 20241008162718.png]]
### Usage

To cite a reference in Obsidian, 
1. click __Open command palette__.
2. chose __Zotero Integration: APA__.
3. Zotero citation window would show up like this4. ![[Pasted image 20241008163513.png]]
5. type the name of reference
6. in-text citation is added like this.
    @abernathyPatternsIndustrialInnovation1978
7. choose Pandoc Reference List: Show reference list, then the referents would show up on the right panel8. ![[Pasted image 20241008163726.png]]

		![[Pasted image 20241008163829.png]]
8. copy the contents of __References__, and paste them in the note.

Reference
[How to use Zotero in Obsidian](https://youtu.be/8yMko1m8XSQ?feature=shared)




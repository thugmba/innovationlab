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

How to cite Zotero'item in Obsidian's note.

### Install

It needs to install one plugin in Zotero and two plugins in Obsidian.

1. Install [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/installation/) plugin in Zotero
2. Install Zotero Integration, Pandoc Reference List plugins in Obsidian

### Configuration

After installing plugins in Obsidian, additional configuration is required for both plugins.

### Zotero Integraion

1. In __Citation Formats__, add a citation style you want. __Name__ is just a name for you to choose from in command palette when you add a citation later.
2. Set the __Output Format__ to __Pandoc__. So, the actual styling task is done by __Pandoc Reference List__ plugin.
![[Pasted image 20241008162336.png]]

### Pandoc Reference List

1. Enable __Pull bibliography from Zotero__.
![[Pasted image 20241008162547.png]]

2. In __Citation style__, choose actual citation style you want. In this example, we choose APA 7 edition.
![[Pasted image 20241008162718.png]]

### Usage

To cite a reference in Obsidian, 
1. click __Open command palette__.
2. chose __Zotero Integration: APA__.
3. Zotero citation window would show up like this4. ![[Pasted image 20241008163513.png]]
5. type the name of reference
6. in-text citation is added like this.
    Abernathy & Utterback (1978)
7. choose Pandoc Reference List: Show reference list, then the referents would show up on the right panel8. ![[Pasted image 20241008163726.png]]

		![[Pasted image 20241008163829.png]]
8. copy the contents of __References__, and paste them in the note.

### References

Signal Processing with Paul (Director). (2024, July 16). _How to use Zotero in Obsidian_ [Video recording]. [https://www.youtube.com/watch?v=8yMko1m8XSQ](https://www.youtube.com/watch?v=8yMko1m8XSQ)

Better BibTeX for Zotero. (n.d.). Retrieved October 9, 2024, from https://retorque.re/zotero-better-bibtex/

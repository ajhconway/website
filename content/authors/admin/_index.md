---
# Display name
title: Alex Conway

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Computer Science Researcher

# Organizations/Affiliations
organizations:
- name: VMware Research Group
  url: "https://research.vmware.com/"

# Short bio (displayed in user profile at end of posts)
bio: My research interests are at the intersection of external memory theory and storage systems.

#education:
#  courses:
#  - course: PhD in Computer Science
#    institution: Rutgers University
#    year: 2020
#  - course: MS in Mathematics
#    institution: Princeton University
#    year: 2011
#  - course: BS in Mathematics
#    institution: Rutgers University
#    year: 2007

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:conway@ajhconway.com'  # For a direct email link, use "mailto:test@example.org".
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=RAYmM1wAAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/ajhconway
- icon: arxiv
  icon_pack: ai
  link: https://arxiv.org/a/conway_a_1.html
- icon: cv
  icon_pack: ai
  link: /files/alex_conway_cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
#user_groups:
#- Researchers
#- Visitors
---

I am a researcher at VMware Research Group, where the principle focus of my
work is the intersection of external memory theory and storage systems. I am
especially interested in key-value stores, file systems, filters and other
systems built on a strong theoretical foundation.

My recent publications include work on [key-value stores for fast
storage](https://www.usenix.org/system/files/atc20-conway.pdf), [file system
aging](https://www.cs.unc.edu/~porter/pubs/fast17.pdf), [external memory hash
tables](http://drops.dagstuhl.de/opus/volltexte/2018/9043/pdf/LIPIcs-ICALP-2018-39.pdf)
and [the analysis of storage optimization
heuristics](https://epubs.siam.org/doi/pdf/10.1137/1.9781611975482.155).

I lead the SplinterDB project. SplinterDB is a general purpose
key-value store built using a new data structure, the size-tiered
$B^\varepsilon$-tree. SplinterDB is designed for outstanding performance on
NVMe and other fast storage hardware, under tough conditions, such as strict memory
limits, small key-value pairs and limits on CPU utilization.

I am a member of the BetrFS team, which built and maintains the BetrFS
prototype file system. BetrFS is designed around the principles of
write-optimization, and is built using variants of $B^\varepsilon$-trees.

---
# `---`之间是用于指定模板参数，比如title，role等

# Display name
title: 样例

# Full Name (for SEO)
first_name: 样例
last_name: 

# Is this the primary user of the site?
superuser: false

# Role/position
role: Professor of Artificial Intelligence

# Organizations/Affiliations
organizations:
  - name: East China Normal University
    url: 'https://www.ecnu.edu.cn'

# Short bio (displayed in user profile at end of posts)
bio: My research interests include distributed robotics, mobile computing and programmable matter.

interests:
  - Artificial Intelligence
  - Computational Linguistics
  - Information Retrieval

education:
  courses:
    - course: PhD in Artificial Intelligence
      institution: Stanford University
      year: 2012
    - course: MEng in Artificial Intelligence
      institution: Massachusetts Institute of Technology
      year: 2009


# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
# For an email link, use "fas" icon pack, "envelope" icon, and a link in the
# form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:test@example.org'
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/GeorgeCushen
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
  - icon: github
    icon_pack: fab
    link: https://github.com/ippqw5

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: false

# user_groups 可选项：
# - Faculty
# - PhD Students
# - Master Students
# - Undergraduate Students
# - Visiting Scholars
user_groups:
  - 博士
  - 硕士
  - 访问学者

# `---`之后，开始写具体的内容，支持markdown语法、latex公式、html标签等
---
> 样例，支持markdown语法、latex公式、html标签

Nelson Bighetti is a professor of artificial intelligence at the Stanford AI Lab. His research interests include distributed robotics, mobile computing and programmable matter. He leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate. This is a <mark>highlighted quote</mark>.
{style="color: red"}

1. First item
   1. A sub-item
2. Another item

- First item
  - A sub-item
- Another item

- [x] Write math example
  - [x] Write diagram example
- [ ] Do something else

{{< spoiler text="Click to view the spoiler" >}}
You found me!
{{< /spoiler >}}

[I'm an external link](https://www.google.com)

[A post]({{< relref "/post/" >}})

[A publication]({{< relref "/publication/" >}})

[A relative link from one post to another post]({{< relref "../" >}})

[Scroll down to a page section with heading *Hi*](#hi)

{{< cite page="/publication/preprint" view="1" >}}
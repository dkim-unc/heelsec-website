---
---

# HeelSec

HeelSec is the computer security group of the [Department of Computer Science](https://www.cs.unc.edu) at the [UNC Chapel Hill](https://www.unc.edu/). HeelSec is led by [Prof. Andrew Kwong](https://andrewkwong.org).

Our research focuses system-level security with a focus on the intersection between hardware and software. Our current project focuses on memory safety and the application of software techniques to exploit hardware vulnerabilities. Please refer to the [projects](/projects) tab to see our current work in progress and [research](/research) for a detailed list of publications. 

##### **Opening: We are looking for talented and motivated PhD students with a strong background in cybersecurity, computer architecture, or systems. Please apply to UNC through the [application system](https://applynow.unc.edu/apply/) and reach out to us with a brief introduction and your CV.**

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

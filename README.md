## About Me

<img  src="IMG_3335_profilepic.jpg" style="width:30%;height:40%" align="right">
Hi! I'm Venky, a software engineer, learning machine learning. I've worked in Computer Vision in grad school, and find deep learning fascinating. I've built pipelines using Apache Ariflow, versioned models using ML flow and deployed models to the google cloud platform.
<br/>Before gradschool, from 2014 to 2021 I worked as a software developer for Cognizant and Accenture. I helped build applications for american commercial insurance clients.
As of 2024, I've completed the Masters in AI program from Khoury College at Northeastern University. I'm looking for full time SWE+ML roles anywhere in the US.
<br/>Please reach me via email : [venks.mail@gmail.com](mailto:venks.mail@gmail.com)


## Education

**MS in Artificial Intelligence, Northeastern University**
<br/>Boston, Jan 2022 - May 2024

**B.E. in Electrical and Electronics Engineering, Anna University**
<br/>Coimbatore, Aug 2010 - May 2014

## Technical Strengths
* Languages : Java, Python, JavaScript, SQL, C++
* Framework : Spring, Agencyportal, Web services
* ML packages/tools : PyTorch, Tensorflow, Numpy, Apache Airflow, MLFlow, Docker

## Certifications
* [Machine Learning in Production](https://coursera.org/share/1223b5ffc9461a2606c1f3f0083f67db)
* [Machine Learning Specialization](https://coursera.org/share/28e8d148ff923a8f7294d802636a7f81)
* SAFe Agile practitioner
* Azure fundamentals

## Experience

**Application Development Team Lead**
Accenture, Pune Feb 2018 - Dec 2021
* Lead an agile team in building an Automated Submission Engine, a new webservice that can use bare bones information from vendors, make anynchronous service calls and return a preliminary quote. This webservice opened up a new avenue of business for the client.
* Implemented new Lines of Business in the Policy Admin application - Automobile, Property, General Liability and Workers Comp.
Techstack : Agencyport-spring framework, Java, Javascript, NodeJs, SQL, XML, XSL, Azure DevOps, Team Foundation Version Control

**Product Specialist**
Cognizant, Hyderabad Sept 2014 - Fec 2018
* Developed a suite of applications - Risk Evaluation, Account Management, Policy Admin and Claims.
* Worked on production support, closed over 200 tickets.
* Met with business/clients to push high quick and high impact changes.
Techstack : Agencyport-spring framework, Java, Javascript, SQL, XML, XSL, Azure DevOps, Subversion


# Researcher

A simple monospaced resume theme for Hugo. It was ported from Jekyll theme
[ankitsultana/researcher](https://github.com/ankitsultana/researcher).

## Screenshot
![screenshot](https://user-images.githubusercontent.com/23409060/188607083-dd087121-16f9-4706-b8b9-a0e4c9e35d93.png)

## Installation
This theme uses Sass to generate CSS files so make sure you have the
*extended* Hugo version installed.

Add the theme to your site's `themes` directory:
```bash
git submodule add https://github.com/ojroques/hugo-researcher.git themes/researcher
# if your website is not managed by git:
# git clone https://github.com/ojroques/hugo-researcher.git themes/researcher
```

Update the theme option in `config.toml`:
```toml
theme = "researcher"
```

## Configuration
A self-explanatory configuration file is present in
[exampleSite/config.toml](https://github.com/ojroques/hugo-researcher/blob/master/exampleSite/config.toml),
along the files of a demo website.

## KaTeX
You can enable [KaTeX](https://katex.org/) (math typesetting) by including
`math: true` in your content files. Or you can enable it globally by setting
`math` to `true` in your project config.

Hugo introduces tags when it sees newlines which breaks KaTeX block
environments. The theme has a `math` shortcode to circumvent this issue:
```md
{{< math >}}
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
{{< /math >}}
```
Check [this
issue](https://github.com/ojroques/hugo-researcher/issues/1#issuecomment-697247056)
for more details.

## License
[GPL-3.0 License](https://github.com/ojroques/hugo-researcher/blob/master/LICENSE)

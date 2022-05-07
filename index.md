## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/jotkim/CMSC320Final/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

```markdown
import requests
headers = {
  'Accept': 'application/json'
}

r = requests.get('https://api.planetterp.com/v1/course', params={
  'name': 'MATH140'
}, headers = headers)

print(r.json())
```
{'department': 'MATH', 'course_number': '140', 'title': 'Calculus I', 'description': '<b>Prerequisite:</b> Minimum grade of C- in MATH115. Or must have math eligibility of MATH140 or higher; and math eligibility is based on the Math Placement Test.\n<b>Credit only granted for:</b> MATH120, MATH130, MATH136, MATH140 or MATH220.\nIntroduction to calculus, including functions, limits, continuity, derivatives and applications of the derivative, sketching of graphs of functions, definite and indefinite integrals, and calculation of area. The course is especially recommended for science, engineering and mathematics majors.\n<i>Graphing calculators, or computers, etc., with software appropriate for graphing non-trivial functions and doing non-trivial calculations, will be needed.</i>', 'credits': 4, 'professors': ['Bradford Sanders', 'David Hamilton', 'Denny Gulick', 'Kasso Okoudjou', 'Frances Gulick', 'Terence Long', 'Wujun Zhang', 'Eric Hamilton', 'Amin Gholampour', 'Jonathan Fernandes', 'Timothy Pilachowski', 'Stephen Balady', 'Steven Chadwick', 'Benjamin Manning', 'Arijit Sehanobish', 'Yue Zhao', 'Patrick Brosnan', 'Nathan Manning', 'Ariella Kirsch', 'Arseny Zakharov', 'Christian Rosendal', 'Sean Ballentine', 'Jacob Renn', 'Craig Schlenoff', 'Elizabeth Wilson', 'Paul Koprowski', 'Wei-Hsuan Yu', 'Domingo Ruiz', 'James Murphy', 'Ran Cui', 'Renjie Feng', 'Caleb Ashley', 'Tingyue Gan', 'Cara Peters', 'Matthew Becker', 'Robert Maschal', 'Adam Telatovich', 'Changguang Dong', 'Fei Wang', 'Ke Xue', 'Mestiyage Gunatilleka', 'Ryan Hunter', 'Wiseley Wong', 'Asia Wyatt', 'Jeremiah Emidih', 'Philip Wertheimer', 'Roohollah Ebrahimian', 'Rufus Elemo', 'Archana Khurana', 'Guangyu Xi', 'Sahil Chopra', 'Tao Zhang', 'Zachary Greenberg', 'Jingren Chi', 'Stefan Doboszczak', 'Xuemiao Chen', 'Yordanka Kovacheva', 'Zack Greenberg', 'Kayla Davie', 'Kendall Williams', 'Nelson Moll', 'Eoin Mackall'], 'average_gpa': 2.21995}

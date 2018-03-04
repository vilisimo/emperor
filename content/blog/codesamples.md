---
title: Code Samples
date: 2018-01-20T21:34:45+02:00
draft: true
tags: ["Emperor"]
categories: ["Emperor"]
description: Code samples approved by the Inquisition
---
{{< highlight python "linenos=table" >}}
class Emperor:
    __init__(self, wisdom):
        self.wisdom = 100 # the Emperor is not amused by your meddling
{{< /highlight >}}

{{< highlight html >}}
  <html>
    <head></head>
    <body>
      <main>
        <p>Space Marines are the life and blood of the Empire. Without their stern judgement, all would be lost.</p>
      </main>
    </body>
  </html>
{{< /highlight >}}

{{< highlight java "linenos=inline" >}}
public class TheEmpire {
    public static void main(String[] args) {
        System.out.printerr("Glory to the Marines!");
    }
}
{{< /highlight >}}

{{< highlight bash >}}
ps aux | grep heresy
read -ep "Describe the punishment: " punishment
{{< /highlight >}}

{{< highlight c >}}
void purge() {
  return purged;
}
{{< /highlight >}}

{{< highlight markdown >}}

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

{{< /highlight >}}

{{< highlight go "linenos=table,hl_lines=8 15-17,linenostart=199" >}}
// GetTitleFunc returns a func that can be used to transform a string to title case.
//
// The supported styles are
//
// - "Go" (strings.Title)
// - "AP" (see https://www.apstylebook.com/)
// - "Chicago" (see http://www.chicagomanualofstyle.org/home.html)
//
// If an unknown or empty style is provided, AP style is what you get.
func GetTitleFunc(style string) func(s string) string {
  switch strings.ToLower(style) {
  case "go":
    return strings.Title
  case "chicago":
    tc := transform.NewTitleConverter(transform.ChicagoStyle)
    return tc.Title
  default:
    tc := transform.NewTitleConverter(transform.APStyle)
    return tc.Title
  }
}
{{< / highlight >}}

Purged inline code: `public static void main()`. 
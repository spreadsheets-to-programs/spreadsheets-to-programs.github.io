---
layout: page
title: "From Spreadsheets to Programs"
doodle: "/doodle.png"
---

# From Spreadsheets to Programs
## Data Science and CS1 in Pyret

_This material is part of workshop #403 of SIGCSE 2018. It will be kept
available indefinitely for those at the workshop and for anyone else who'd like
to try out the material!_

_Workshop attendees can give feedback here: [https://goo.gl/VmKcve](https://goo.gl/VmKcve)_

### Links to Workshop Resources

- [Initial Slides about Data-Centric Computing](./pyret-data-cs1.pdf)
- The Workbook ([docx](./spreadsheets-to-programs.docx)) ([pdf](./spreadsheets-to-programs.pdf))
- [Getting Started in Pyret](https://code.pyret.org/editor#share=1MoQ8YxevbLP2ohiXD5NiwqsBsdoYIrUw)
- [Animals Dataset](https://code.pyret.org/editor#share=0BzzMl1BJlJDkYkhKMG51VlRiWk0)
- [Starter file for working with data definitions](https://code.pyret.org/editor#share=1bDWh4mi5D2XCY6PE5h0qxHTDubxaraES)

Partway through the workshop, choose from one of these starter data sets (all
of which are available as part of [Boostrap: Data
Science](http://www.bootstrapworld.org/materials/spring2018/courses/data-science/english/units/unit2/index.html#lesson_ChooseYourDataset9650))
to formulate and answer questions:

 - [Movies Dataset](https://docs.google.com/spreadsheets/d/1SaR2M6Z-s40UuRg3u1aQU-G1GVdcm0RgHpqQ9LNmSQk) (and the [Starter file](https://code.pyret.org/editor#share=1KaHf2DSd5iJ17UsRd61jljsWR_HqRQY2) for this dataset)
 - [School Dataset](https://docs.google.com/spreadsheets/d/1yHPM-poscv6azh59aMwElfUP67P3fMESorVjtMwsFa0) (and the [Starter file](https://code.pyret.org/editor#share=1371QVz9uLJKCiX_Q3bR93ZZ5EKhAxZoR) for this dataset)
 - [US Income Dataset](https://docs.google.com/spreadsheets/d/1cIxBSQebGejWK7S_Iy6cDFSIpD-60x8oG7IvrfCtHbw) (and the [Starter file](https://code.pyret.org/editor#share=1lVDBQiAze_NjH69rWcFi15ApbNPZWXOk) for this dataset)
 - [US Presidents Dataset](https://docs.google.com/spreadsheets/d/14er5Mh443Lb5SIFxXZHdAnLCuQZaA8O6qtgGlibQuEg) (and the [Starter file](https://code.pyret.org/editor#share=18Ux-O_c78jnZ4cFjTwvaZzaBJOch9cTK) for this dataset)
 - [Countries of the World Dataset](https://docs.google.com/spreadsheets/d/1lOFsofXJNIMKAM8g4Zn688jIdbAK68ovAnzmfuwFd9M) (and the [Starter file](https://code.pyret.org/editor#share=1V1u_kINuc6PCOWZ0WF7a2oZSLbrzRitg) for this dataset)
 - [Music](https://docs.google.com/spreadsheets/d/1-mrDSjS-rWMdiMAIptFS_PHVUFO06lUpYNCiGkYj51s) (and the [Starter file](https://code.pyret.org/editor#share=1EHpLimHbsZkSie23Dt-COhTDtNQ0_g1Z) for this dataset)
 - [State Demographics](https://docs.google.com/spreadsheets/d/1HJ6wR4IH9j0hqbaP4OXeChOVMbVMyV0vBMu25NUiw1w) (and the [Starter file](https://code.pyret.org/editor#share=1okOF06x6_UtMgnM8yi6dIGH6ZfBrpEQM) for this dataset)
 - [New York City Restaurant Health Inspections](https://docs.google.com/spreadsheets/d/182UAmtxaBjIY3cGB9fy8tsl1q3ZJ0fcP4m38i9Sr5l0) (and the [Starter file](https://code.pyret.org/editor#share=1HpAIsC_3sDWYgtIj0iwgch81MllIa-Yy) for this dataset)
 - [Pokemon Dataset](https://docs.google.com/spreadsheets/d/1F5Q2HwyhrhzMBivKNA2qpgUroqGWpDTUKcF3p82pVDA) (and the [Starter file](https://code.pyret.org/editor#share=1h3pCuuc0AchFZidLV-9553kGhpRKyYxP) for this dataset)
 - [IGN Video Game Reviews Dataset](https://docs.google.com/spreadsheets/d/126sJLFP8kenombJx5CtR-9D88jgbI_vKlYq30PWT41g) (and the [Starter file](https://code.pyret.org/editor#share=1H3-aDMoCNCJtRoUpJfPFRUy2JuhmBNFJ) for this dataset)
 - [2016 Presidential Primary Election Dataset](https://docs.google.com/spreadsheets/d/1WMJMNqkwuo1vbL0O_C81BPA-R2TFcLWEMUi7cn_ptow) (and the [Starter file](https://code.pyret.org/editor#share=1U_R0ZoRRvUwKy58m9cgJ6AyDHWW1Oh7-) for this dataset)
 - [US Cancer Rates Dataset](https://docs.google.com/spreadsheets/d/1Fyp-h8sSggYPHIpvrtBzSrKGa6bZioy1lMTKIC--RH0) (and the [Starter file](https://code.pyret.org/editor#share=1Kd9Zi4Z0jKkyxV7rHCw4nNQqbhgpT2Qi) for this dataset)
 - [Summer Olympic Medals Dataset](https://docs.google.com/spreadsheets/d/19bmTJd2soUvg6FUDIW546jPtiWOERFm2o9z7TLBNTbc) (and the [Starter file](https://code.pyret.org/editor#share=1HubbGjtE96e3wt0EZqlVWtKstmyPpDd_) for this dataset)
 - [Winter Olympic Medals Dataset](https://docs.google.com/spreadsheets/d/1ZJ9d4BtF6xOqyBdGgjW-vCeJ7-rOHWIhGMiBNwqCEVo) (and the [Starter file](https://code.pyret.org/editor#share=1QvKr16tceg0wQ9vLfu-iFiZEpUdw5I2L) for this dataset)
 - [MLB Hitting Stats Dataset](https://docs.google.com/spreadsheets/d/157Bi2kniAJybuV1X_9h4Z6DaZSVPK3vPf697feXcyv8) (and the [Starter file](https://code.pyret.org/editor#share=1_d80_yLylUXz32QrEsN9EjtHEHJ8gB34) for this dataset)
 - [NFL Touchdown Leaders](https://docs.google.com/spreadsheets/d/156Q1HxZ-MJvByEKVoIMPmVELtQwiUb3uJEszmkndrMs) (and the [Starter file](https://code.pyret.org/editor#share=1wb4fwcItuACau5j2g0Op_IWTDx9EN4iZ) for this dataset)
 - [NFL Quarterback Win/Loss Records](https://docs.google.com/spreadsheets/d/1aVQz1PxO7LYM131LpwJUH_5fjjIF9L0JlhDvR75c5HY) (and the [Starter file](https://code.pyret.org/editor#share=1k-VFc99jnKJeX6_C_9Horo1RUq7yz9oM) for this dataset)
 - [Purebred Pedigree Dataset](https://docs.google.com/spreadsheets/d/1lOyPpnL7JgJEsCLQbUudiZJu8OTkpcn1-CCI9qLd3N8) (and the [Starter file](https://code.pyret.org/editor#share=1K008hd9j_mqzXMd3mBpvMkzD0c5U3LeO) for this dataset)

For grouping tables by column, you can include this line at the top of
your file:

```
import shared-gdrive("Table group operations", "1JdrIKGQGaSsWMlTs6HUPUna8Uu-co3EU") as T
```

which defines:

```
T.group :: (t :: Table), (column :: String) -> Table
T.count :: (t :: Table), (column :: String) -> Table
```

You can see the group-by code here:

[https://code.pyret.org/editor#share=1JdrIKGQGaSsWMlTs6HUPUna8Uu-co3EU](https://code.pyret.org/editor#share=1JdrIKGQGaSsWMlTs6HUPUna8Uu-co3EU)


### Credits and Further Reading

The materials for this workshop remix and draw inspiration from several places:

- [Programming and Programming Languages](http://papl.cs.brown.edu/2017)
- [A Data-Centric Introduction to Programming](http://cs.brown.edu/courses/csci0050/2017/)
- [Bootstrap: Data Science](http://www.bootstrapworld.org/materials/data-science/)
- [How to Design Programs](http://htdp.org/)


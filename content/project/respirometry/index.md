---
title: Measuring Metabolic Rate in honeybees 
subtitle: Respirometry 
author: Julian Cassano
categories:
date: "2020-08-01"
draft: false
excerpt: In this project I use cutting edge methods to quantitatively measure metabolic rate for honeybee individuals.
layout: single
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/jscassano/FMR_Analysis_22.git
tags:
---
---
### How do we measure metabolic rate in an organism?
![FMR_example](/img/FMR_example.jpg)
Metabolic rate is considered a fundamental feature of all living organisms and at CSU's Honeybee Behavior lab, I utilize flow-through respirometry to quantitatively measure a honeybee's metabolic rate. This mechanism allows us to accurately measure how much carbon dioxide a bee emits when it performs different behaviors. In a nutshell, we measure how hard these bees are breathing. 

This is made possible by first using a FoxBox respirometry setup (Sable Systems) that controlled outflow and inflow of air into a closed system containing our honeybee. We then use ExpeData software to accurately measure the amount of carbon dioxide produced by this bee and plot it on a time axis. 

From this data, we carefully monitor and record various behaviors the bee is exhibiting such as flying and resting. When I pair this with carbon dioxide output data (VCO2) I use R studio to calculate a Flight Metabolic Rate (FMR) and a Resting Metabolic Rate (RMR) for each individual. 




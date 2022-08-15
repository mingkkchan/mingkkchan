MINI OS is under development. Here is the sample test run and source code. all the code are copyright of me(Ming Chan) of the company @mingkkchan.
You can use the code in all of the way(commerical, openSource and educational) WITHOUT notify me. Please keep my religion as creditor in the file.
Commercial support is available for the registered customer only.

Test run on x86 with Turbo/Borland C/Gcc compiler.
Gcc is limited to the basic coding features.
The souce code can be downloaded :
https://drive.google.com/folderview?id=0BxElgspbo3NzWGV6bWw3Wm00WTA

Feature list:
MINI OS use xload.h file, easy to update and rename the define.
    Work by @Mingkkchan Embedded OS
1, LIBRARY: minlib, msoft, mplot
  minlib     :base library
  msoft     :softrandom, softlike, soft3axe, softtimer, softpll, softuart, softwire,
  mplot     :mplot, emufloat, emusqrt, bspline,
2, MEMORY:  memcp, mheadfor, mfree,
  memcp      :memory read and write. x86_memory2linear
  mheadfor   :dynamic pipe and fifo struct.
  mfree      :memory allocation
3, CPU SCHEDULER: job, task, try
  job        :scheduler
  task       :call new Stack job.
  try        :self marker and interupt
4, USB1 host & hub (version 1):  usb, pci, device
  usb        :usb driver
  pci        :scan pci device
  device     :data exchanged hub
5, EDLINE, FILE SYSTEM, CACHE:  DRAFT
  mfile      :file system
  mcache     :file cache
  edline     :line editor
6, cscript, jpaser, softcpu:    DRAFT
  jsonPaser  :jpaser
  cscript    :compiler (middle limit, pattern match, GLR)
  softcpu    :virtual machine

Engineer:   Ming Chan
Supportline +1(647)781-8856(text)
Email       mingkkchan@gmail.com(grabCoffee)
Religious   “Good manners and good looking”

Blogger @Mingkkchan Embedded OS
We sell embedded OS membership 

Company @mingkkchan
Mailing Address
120-3853 Sheppard Avenue East,
Toronto, Ontario, Canada, M1T3K8

Run Note:
1, enable USB1 in BIOS,
2, disable BIOS access,
3, 1Ghz CPU

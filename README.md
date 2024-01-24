# bookmarks

I was a little annoyed by not finding resources (documentation, tutorials,
videos, recipes, or what ever) that I knew I had looked up before. I needed a
why to manage my bookmarks. Somehow browser bookmarks don't work well for me,
because I work on different machines, in different locations, with different
browsers, etc. I know there are bookmark managers that keep your bookmarks
synchronized between different computers and browsers, but somehow I haven't
found one that I like. Maybe I haven't look long enough, I don't know. But I
wanted to collect all my bookmarks in one central location, that I can access
from anywhere. This is what this repo is for.

I don't know what will develop out of it. I might create a database and a
django app to access it in the future. Or maybe come up with some other
solution, but for now this README file will be the place where I just drop all
my bookmarks in a hopefully somewhat structured way.

Some of the links might be useful for others, other links might be pretty
specific to my needs. I still thought, I would make it a public, so anyone that
finds my list of links useful is welcome to use it.


## Programming


### Shell Scripting

- [Jürgen Wolf's book Shell-Programmierung (German)](https://openbook.rheinwerk-verlag.de/shell_programmierung/)


### Python

- [Python documentation](https://docs.python.org/3/)
- [NumPy Reference](https://numpy.org/doc/stable/reference/index.html)
- [matplotlib Reference](https://matplotlib.org/stable/api/index)
- [pandas Reference](https://pandas.pydata.org/docs/reference/index.html)
- [scikit learn Reference](https://scikit-learn.org/stable/modules/classes.html)
- [Python API reference for plotly](https://plotly.com/python-api-reference/index.html)
- [Top 10 Mistakes that Django Developers Make](https://www.toptal.com/django/django-top-10-mistakes)
- [Scikit-Learn Pipeline Examples](https://queirozf.com/entries/scikit-learn-pipeline-examples#text-classification-nlp)
- [Stock Prediction with ML](https://alphascientist.com/data_management.html)
- [Przemek Rogala's Jinja2 Tutorial](https://ttl255.com/jinja2-tutorial-part-1-introduction-and-variable-substitution/)


### Django

- [Django Project](https://www.djangoproject.com/)
- [The Django Book](https://djangobook.com/)
- [Corey Schafer's Django Series](https://www.youtube.com/playlist?list=PLLtIxaRk6P3JRiiW1SAV2BLhuuSSCULRn)
- [django Documentation](https://docs.djangoproject.com/en/4.0/)
- [Django Best Practices](https://django-best-practices.readthedocs.io/en/latest/index.html)


### Semaphore vs Mutex

- [Quantum Leaps: Modern Embedded Systems Programming: great video about semaphores](https://www.youtube.com/watch?v=IrDcBZX0AdY&list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM&index=28)
- [Quantum Leaps: Modern Embedded Systems Programming: great video about mutexes](https://www.youtube.com/watch?v=kcpVI3IjUUM&list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM&index=29)

  It also explains nicely the difference between the `Priority Ceiling Protocol` and the `Priority Inheritance Protocol` and why the first one is probably preferred in most cases.
  
- [Great article about Mutexes](https://www.smxrtos.com/articles/techppr/mutex.htm)
  
  It mentions disadantages of the `Priority Ceiling Protocol` and explains situations when it might not be preferred over the `Priority Inheritance Protocol`. It also talks about deadlocks.
  
- [Digikey: Nice article about Priority Inversion](https://www.digikey.at/en/maker/projects/introduction-to-rtos-solution-to-part-11-priority-inversion/abf4b8f7cd4a4c70bece35678d178321)

  It nicely explains why the `Priority Ceiling Protocol` and the `Priority Inheritance Protocol` only prevent unbounded priority inversion but not bounded priority inversion.
  
- [Digikey: accompanying video ot the previous article](https://www.youtube.com/watch?v=C2xKhxROmhA)
- [Good explanation of Sempahores and Mutexes (in Java)](https://scrutinybykhimaanshu.blogspot.com/2019/08/all-about-java-semaphore.html)
- 


## Linux

- [The Linux Foundation](https://linuxfoundation.org/)
- [DNS Dumpster](https://dnsdumpster.com/)
- [Linux Kernel Browser](https://elixir.bootlin.com/)


### Arch

- [ArchWiki](https://wiki.archlinux.org/)
- [Pacman Package Upgrad Issues (GPG Key)](https://bbs.archlinux.org/viewtopic.php?id=233362)
- [Install Nerd Font on Arch Linux – Behova.net](https://www.behova.net/install-nerd-font-on-arch-linux/)


### Yocto

- [Yocto Project Documentation](https://docs.yoctoproject.org/index.html)
- [Yocto Project Reference Manual](https://docs.yoctoproject.org/ref-manual/index.html)
- [What I wish I’d known about Yocto Project](https://docs.yoctoproject.org/what-i-wish-id-known.html)
- [The Yocto Project Development Tasks Manual](https://docs.yoctoproject.org/dev-manual/intro.html#)
- [Yocto Project Wiki](https://wiki.yoctoproject.org/wiki/Main_Page)
- [Yocto Project Git Repo](https://git.yoctoproject.org/)
- [Yocto Project Compatible Layers](https://www.yoctoproject.org/development/yocto-project-compatible-layers/)
- [OpenEmbedded Layer Index](https://layers.openembedded.org/)


## Open Source

- [Good overview and explanation of open source licenses](https://www.tldrlegal.com/)


### Conferences

- [Fosdem](https://fosdem.org/)
- [Open Source Summit (Europe)](https://events.linuxfoundation.org/open-source-summit-europe/)
- [Embedded Linux Conference](https://www.embeddedlinuxconference.com/)


## Git

- [Git Reference Manual](https://git-scm.com/docs)
- [Pro Git](https://git-scm.com/book/en/v2)
- [Reset Demystified](https://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified)
- [Git From the Bits Up](https://www.youtube.com/watch?v=MYP56QJpDr4)
- [Seth Robertson's "Git Best Practices"](http://sethrobertson.github.io/GitBestPractices/)


## xmonad

- [xmonad](https://xmonad.org/)
- [XMonad Configuration Tutorial](https://xmonad.org/TUTORIAL.html)
- [Blog Post: Xmonad and Xmobar for laptop](https://gumirov.xyz/posts/f15c07386b770f9be62364935f64db1f37853cf1500d55ca795064165abed740/)


## Ansible

- [Ansible Homepage](https://www.ansible.com/)
- [Ansible Galaxy](https://galaxy.ansible.com/)
- [Book: Ansible for DevOps](https://leanpub.com/ansible-for-devops)
- [Jeff Geerling's Ansible 101 Series](https://www.youtube.com/watch?v=goclfp6a2IQ&list=PL2_OBreMn7FqZkvMYt6ATmgC0KAGGJNAN)


## kubernetes

- [Creating a cluster with kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/)


## NeoMutt

- [NeoMutt Project Homepage](https://neomutt.org/)
- [Reply from address the original message was sent to](https://unix.stackexchange.com/questions/637029/neomutt-reply-to-email-from-the-adress-the-original-message-was-sent-to-auto)


## GPG

- [A Practical Guide to GPG](https://www.linuxbabe.com/security/a-practical-guide-to-gpg-part-1-generate-your-keypair)
- [Arch Wiki: GnuPG](https://wiki.archlinux.org/title/GnuPG#gpg-agent)


## Keyring

- [Arch Wiki: GNOME/Keyring](https://wiki.archlinux.org/title/GNOME/Keyring)
- [Interesting threat about PAM and pinentry](https://superuser.com/questions/1460356/gpg-autologin-with-pam-pinentry)


## Bug Hunting


### Database And Search Engins

- [National Vulnerability Database](https://nvd.nist.gov/vuln/full-listing)
- [Exploit Database](https://www.exploit-db.com/)
- [Shodan](https://www.shodan.io/)


### Learning Resources

- [Try Hack Me](https://tryhackme.com/)


## Hosting Websites


### DSGVO (German)

- [F\*ck you DSGVO](https://www.kevinpapst.de/persoenliche-erfahrungen-mit-der-dsgvo/)
- [Frühjahrsputz mit DSGVO](https://www.arminhanisch.de/2018/03/dsgvo-umstellung/)


### Jekyll

- [Jekyll](https://jekyllrb.com/)
- [Cookie consent](https://jekyllcodex.org/without-plugin/cookie-consent/)


## Scuba Diving

- [VDST](https://www.vdst.de/)
- [SSI](https://www.divessi.com/)
- [PADI](https://www.padi.com/)


### Statistics

- [How Many Divers Are There?](http://www.undercurrent.org/UCnow/dive_magazine/2007/HowManyDivers200705.html)
- [PADI Statistics](https://www.padi.com/corporate/company-info)
- [Training Scuba Divers: A Fatality and Risk Analysis](http://d35gjurzz1vdcl.cloudfront.net/ftw-files/Day1/Evidence/5.pdf)


## Math

- [The awesome youtube channel "3Blue1Brown"](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)
- [3Blue1Brown's series: Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [Short useful explanation about Discrete Fourier Transformations](https://www.youtube.com/watch?v=mkGsMWi_j4Q)


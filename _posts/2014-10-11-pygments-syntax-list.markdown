---
author: chris.hill
comments: true
date: 2014-10-14
excerpt: pygments语法汇总
layout: post
slug: pygments-syntax-list
title: pygments语法汇总 
categories:
- it运维
tags:
- Linux
---

* * *

pygments语法汇总

#常用标记

```
vim
bash, sh
css
diff, udiff
django, jinja
html+django, html+jinja
html+php
ini, cfg
html
js, javascript
lua
make, makefile, mf, bsdmake
mysql
nginx
php
python
sql
squidconf, squid.conf, squid
tex, latex
text
yaml
```

查询命令

```sh
pygmentize -L|less
```
#pygment支持的全部类型


```
* abap:
    ABAP (filenames *.abap)
* antlr-as, antlr-actionscript:
    ANTLR With ActionScript Target (filenames *.G, *.g)
* antlr-cpp:
    ANTLR With CPP Target (filenames *.G, *.g)
* antlr-csharp, antlr-c#:
    ANTLR With C# Target (filenames *.G, *.g)
* antlr-java:
    ANTLR With Java Target (filenames *.G, *.g)
* antlr-objc:
    ANTLR With ObjectiveC Target (filenames *.G, *.g)
* antlr-perl:
    ANTLR With Perl Target (filenames *.G, *.g)
* antlr-python:
    ANTLR With Python Target (filenames *.G, *.g)
* antlr-ruby, antlr-rb:
    ANTLR With Ruby Target (filenames *.G, *.g)
* antlr:
    ANTLR
* apacheconf, aconf, apache:
    ApacheConf (filenames .htaccess, apache.conf, apache2.conf)
* applescript:
    AppleScript (filenames *.applescript)

* as, actionscript:
    ActionScript (filenames *.as)
* as3, actionscript3:
    ActionScript 3 (filenames *.as)
* aspx-cs:
    aspx-cs (filenames *.aspx, *.asax, *.ascx, *.ashx, *.asmx, *.axd)
* aspx-vb:
    aspx-vb (filenames *.aspx, *.asax, *.ascx, *.ashx, *.asmx, *.axd)
* basemake:
    Makefile
* bash, sh:
    Bash (filenames *.sh, *.ebuild, *.eclass)
* bat:
    Batchfile (filenames *.bat, *.cmd)
* bbcode:
    BBCode
* befunge:
    Befunge (filenames *.befunge)
* boo:
    Boo (filenames *.boo)
* brainfuck, bf:
    Brainfuck (filenames *.bf, *.b)
* c-objdump:
    c-objdump (filenames *.c-objdump)
* c:
    C (filenames *.c, *.h)
* cheetah, spitfire:
    Cheetah (filenames *.tmpl, *.spt)
* clojure, clj:
    Clojure (filenames *.clj)
* common-lisp, cl:
    Common Lisp (filenames *.cl, *.lisp, *.el)
* console:
    Bash Session (filenames *.sh-session)
* control:
    Debian Control file (filenames control)
* cpp, c++:
    C++ (filenames *.cpp, *.hpp, *.c++, *.h++, *.cc, *.hh, *.cxx, *.hxx)
* cpp-objdump, c++-objdumb, cxx-objdump:
    cpp-objdump (filenames *.cpp-objdump, *.c++-objdump, *.cxx-objdump)
* csharp, c#:
    C# (filenames *.cs)
* css+django, css+jinja:
    CSS+Django/Jinja
* css+erb, css+ruby:
    CSS+Ruby
* css+genshitext, css+genshi:
    CSS+Genshi Text
* css+mako:
    CSS+Mako
* css+myghty:
    CSS+Myghty
* css+php:
    CSS+PHP
* css+smarty:
    CSS+Smarty
* css:
    CSS (filenames *.css)
* cython, pyx:
    Cython (filenames *.pyx, *.pxd, *.pxi)
* d-objdump:
    d-objdump (filenames *.d-objdump)
* d:
    D (filenames *.d, *.di)
* delphi, pas, pascal, objectpascal:
    Delphi (filenames *.pas)
* diff, udiff:
    Diff (filenames *.diff, *.patch)
* django, jinja:
    Django/Jinja
* dpatch:
    Darcs Patch (filenames *.dpatch, *.darcspatch)
* dylan:
    Dylan (filenames *.dylan)
* erb:
    ERB
* erl:
    Erlang erl session (filenames *.erl-sh)
* erlang:
    Erlang (filenames *.erl, *.hrl)
* evoque:
    Evoque (filenames *.evoque)
* fortran:
    Fortran (filenames *.f, *.f90)
* gas:
    GAS (filenames *.s, *.S)
* genshi, kid, xml+genshi, xml+kid:
    Genshi (filenames *.kid)
* genshitext:
    Genshi Text
* glsl:
    GLSL (filenames *.vert, *.frag, *.geo)
* gnuplot:
    Gnuplot (filenames *.plot, *.plt)
* groff, nroff, man:
    Groff (filenames *.[1234567], *.man)
* haskell, hs:
    Haskell (filenames *.hs)
* html+cheetah, html+spitfire:
    HTML+Cheetah
* html+django, html+jinja:
    HTML+Django/Jinja
* html+evoque:
    HTML+Evoque (filenames *.html)
* html+genshi, html+kid:
    HTML+Genshi
* html+mako:
    HTML+Mako
* html+myghty:
    HTML+Myghty
* html+php:
    HTML+PHP (filenames *.phtml)
* html+smarty:
    HTML+Smarty
* html:
    HTML (filenames *.html, *.htm, *.xhtml, *.xslt)
* ini, cfg:
    INI (filenames *.ini, *.cfg, *.properties)
* io:
    Io (filenames *.io)
* irc:
    IRC logs (filenames *.weechatlog)
* java:
    Java (filenames *.java)
* js+cheetah, javascript+cheetah, js+spitfire, javascript+spitfire:
    JavaScript+Cheetah
* js+django, javascript+django, js+jinja, javascript+jinja:
    JavaScript+Django/Jinja
* js+erb, javascript+erb, js+ruby, javascript+ruby:
    JavaScript+Ruby
* js+genshitext, js+genshi, javascript+genshitext, javascript+genshi:
    JavaScript+Genshi Text
* js+mako, javascript+mako:
    JavaScript+Mako
* js+myghty, javascript+myghty:
    JavaScript+Myghty
* js+php, javascript+php:
    JavaScript+PHP
* js+smarty, javascript+smarty:
    JavaScript+Smarty
* js, javascript:
    JavaScript (filenames *.js)
* jsp:
    Java Server Page (filenames *.jsp)
* lhs, literate-haskell:
    Literate Haskell (filenames *.lhs)
* lighty, lighttpd:
    Lighttpd configuration file
* llvm:
    LLVM (filenames *.ll)
* logtalk:
    Logtalk (filenames *.lgt)
* lua:
    Lua (filenames *.lua)
* make, makefile, mf, bsdmake:
    Makefile (filenames *.mak, Makefile, makefile, Makefile.*, GNUmakefile)
* mako:
    Mako (filenames *.mao)
* matlab, octave:
    Matlab (filenames *.m)
* matlabsession:
    Matlab session
* minid:
    MiniD (filenames *.md)
* modelica:
    Modelica (filenames *.mo)
* moocode:
    MOOCode (filenames *.moo)
* mupad:
    MuPAD (filenames *.mu)
* mxml:
    MXML (filenames *.mxml)
* myghty:
    Myghty (filenames *.myt, autodelegate)
* mysql:
    MySQL
* nasm:
    NASM (filenames *.asm, *.ASM)
* newspeak:
    Newspeak (filenames *.ns2)
* nginx:
    Nginx configuration file
* numpy:
    NumPy
* objdump:
    objdump (filenames *.objdump)
* objective-c, objectivec, obj-c, objc:
    Objective-C (filenames *.m)
* ocaml:
    OCaml (filenames *.ml, *.mli, *.mll, *.mly)
* perl, pl:
    Perl (filenames *.pl, *.pm)
* php, php3, php4, php5:
    PHP (filenames *.php, *.php[345])
* pot, po:
    Gettext Catalog (filenames *.pot, *.po)
* pov:
    POVRay (filenames *.pov, *.inc)
* prolog:
    Prolog (filenames *.prolog, *.pro, *.pl)
* py3tb:
    Python 3.0 Traceback (filenames *.py3tb)
* pycon:
    Python console session
* pytb:
    Python Traceback (filenames *.pytb)
* python, py:
    Python (filenames *.py, *.pyw, *.sc, SConstruct, SConscript)
* python3, py3:
    Python 3
* ragel-c:
    Ragel in C Host (filenames *.rl)
* ragel-cpp:
    Ragel in CPP Host (filenames *.rl)
* ragel-d:
    Ragel in D Host (filenames *.rl)
* ragel-em:
    Embedded Ragel (filenames *.rl)
* ragel-java:
    Ragel in Java Host (filenames *.rl)
* ragel-objc:
    Ragel in Objective C Host (filenames *.rl)
* ragel-ruby, ragel-rb:
    Ragel in Ruby Host (filenames *.rl)
* ragel:
    Ragel
* raw:
    Raw token data
* rb, ruby:
    Ruby (filenames *.rb, *.rbw, Rakefile, *.rake, *.gemspec, *.rbx)
* rbcon, irb:
    Ruby irb session
* rebol:
    REBOL (filenames *.r, *.r3)
* redcode:
    Redcode (filenames *.cw)
* rhtml, html+erb, html+ruby:
    RHTML (filenames *.rhtml)
* rst, rest, restructuredtext:
    reStructuredText (filenames *.rst, *.rest)
* scala:
    Scala (filenames *.scala)
* scheme, scm:
    Scheme (filenames *.scm)
* smalltalk, squeak:
    Smalltalk (filenames *.st)
* smarty:
    Smarty (filenames *.tpl)
* sourceslist, sources.list:
    Debian Sourcelist (filenames sources.list)
* splus, s, r:
    S (filenames *.S, *.R)
* sql:
    SQL (filenames *.sql)
* sqlite3:
    sqlite3con (filenames *.sqlite3-console)
* squidconf, squid.conf, squid:
    SquidConf (filenames squid.conf)
* tcl:
    Tcl (filenames *.tcl)
* tcsh, csh:
    Tcsh (filenames *.tcsh, *.csh)
* tex, latex:
    TeX (filenames *.tex, *.aux, *.toc)
* text:
    Text only (filenames *.txt)
* trac-wiki, moin:
    MoinMoin/Trac Wiki markup
* vala, vapi:
    Vala (filenames *.vala, *.vapi)
* vb.net, vbnet:
    VB.net (filenames *.vb, *.bas)
* vim:
    VimL (filenames *.vim, .vimrc)
* xml+cheetah, xml+spitfire:
    XML+Cheetah
* xml+django, xml+jinja:
    XML+Django/Jinja
* xml+erb, xml+ruby:
    XML+Ruby
* xml+evoque:
    XML+Evoque (filenames *.xml)
* xml+mako:
    XML+Mako
* xml+myghty:
    XML+Myghty
* xml+php:
    XML+PHP
* xml+smarty:
    XML+Smarty
* xml:
    XML (filenames *.xml, *.xsl, *.rss, *.xslt, *.xsd, *.wsdl)
* xslt:
    XSLT (filenames *.xsl, *.xslt)
* yaml:
    YAML (filenames *.yaml, *.yml)

```

#参考资料

http://pygments.org






* * *


作者：chris hill



微博：[@翻滚的蜗牛blog](http://www.weibo.com/weittor)


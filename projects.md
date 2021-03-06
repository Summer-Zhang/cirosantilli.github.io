---
title: Projects
---

The key content previously on this page was moved to the following sections:

- [/#the-most-important-projects-done-by-ciro-santilli](/#the-most-important-projects-done-by-ciro-santilli)

{{ site.toc }}

## Size scale

Some of the contributions are subjectively self evaluated based on:

-   How many significant lines changed (no indentation changes, moves, mass refactoring, trivial tests, etc.):

    | 0 | only trivial changes |
    | 1 | < 20                 |
    | 2 | < 150                |
    | 3 | > 150                |
    {: #grading-table}

-   How hard it was to make it. 4 algorithmic lines are harder than 100 web development / documentation lines.

## Patches

### Merged by others

Only patches which were reviewed by at least one person with push permission will be listed here.

This may also include patches which were rejected in favor of another patch, but strongly influenced the merged patch.

| Date    | Project                      | Size | Description                                                                                                                                                                    |
|---------|------------------------------|------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2019-09 | [KaTeX][]                    | 1    | [Create globalGroup option to place definitions in global scope](https://github.com/KaTeX/KaTeX/pull/2091)                                                                     |
| 2018-06 | raspi3-tutorial              | 0    | [Explain how to see UART1](https://github.com/bztsrc/raspi3-tutorial/pull/34)                                                                                                  |
| 2018-05 | [Buildroot][]                | 1    | [ltp-testsuite: add --with-open-posix-testsuite](https://github.com/buildroot/buildroot/commit/45719594d08024df97db55333f8ab3ba2b4fc23e)                                       |
| 2018-03 | [Buildroot][]                | 1    | [qemu_x86_64_defconfig: fix kernel header version after bump to 4.15](https://github.com/buildroot/buildroot/commit/8a6e30efdeb9f31d51a92ed465373f4128f55e8a)                  |
| 2017-11 | [Cocos2d-x][]                | 1    | [Recreate libfmod.so.6 symlinks](https://github.com/cocos2d/cocos2d-x-3rd-party-libs-bin/pull/304)                                                                             |
| 2017-10 | [Cocos2d-x][]                | 1    | [Make bullet use -fPIC](https://github.com/cocos2d/cocos2d-x-3rd-party-libs-src/pull/155#issuecomment-336760545)                                                               |
| 2017-07 | [OpenCL headers][]           | 0    | [C11 anonymous structs / unions should allow xyz notation for vector types](https://github.com/KhronosGroup/OpenCL-Headers/issues/18)                                          |
| 2017-06 | [linux-insides][]            | 0    | [Mention Buildroot in addition to ivandaviov/minimal](https://github.com/0xAX/linux-insides/pull/489)                                                                          |
| 2017-06 | [opengl-tutorial][]          | 0    | [Use existing empty layout on feed.xml](https://github.com/opengl-tutorials/ogl/pull/17)                                                                                       |
| 2017-04 | [Tiny Renderer][]            | 0    | [Add gitignore](https://github.com/ssloy/tinyrenderer/pull/10)                                                                                                                 |
| 2017-02 | [Vulkan-Loader][]            | 0    | [Use nproc instead of ncpu](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers/pull/1536)                                                                        |
| 2017-01 | [Boost Geometry][]           | 1    | [What is "QPoint::double" in doc/example_adapting_a_legacy_geometry_object_model.qbk ?](https://github.com/boostorg/geometry/issues/376)                                       |
| 2016-12 | [freetype-gl][]              | 1    | [GLFW Ubuntu package works on 16.10](https://github.com/rougier/freetype-gl/pull/144#event-905730810)                                                                          |
| 2016-11 | [vim-snippets][]             | 1    | [Add C variable printf debug snippets](https://github.com/honza/vim-snippets/pull/816)                                                                                         |
| 2016-09 | [Android Vulkan Tutorials][] | 1    | [Add a world to the gui_overlay_plugin_time example](https://bitbucket.org/osrf/gazebo/pull-requests/2460/add-a-world-to-the-gui_overlay_plugin_time/diff)                     |
| 2016-07 | [Android Vulkan Tutorials][] | 1    | [Use android API 24](https://github.com/googlesamples/android-vulkan-tutorials/pull/12)                                                                                        |
| 2016-07 | [minimal linux live][]       | 0    | [Fix time sh instead of sh time](https://github.com/ivandavidov/minimal/pull/30)                                                                                               |
| 2016-06 | [ghdl][]                     | 0    | [Typo severals -> several in Invoking doc](https://github.com/tgingold/ghdl/pull/81)                                                                                           |
| 2016-06 | [ghdl][]                     | 1    | [Document GCC backend needed to generate executables](https://github.com/tgingold/ghdl/pull/80)                                                                                |
| 2016-06 | [ghdl][]                     | 0    | [Typo debugger -> debugged in BUILD.txt](https://github.com/tgingold/ghdl/pull/79)                                                                                             |
| 2016-06 | [ghdl][]                     | 0    | [Typo carray -> carry in full adder example](https://github.com/tgingold/ghdl/pull/77)                                                                                         |
| 2016-05 | [facedetect][]               | 1    | [Add example to extract faces with imagemagick](https://github.com/wavexx/facedetect/pull/7#event-675223551)                                                                   |
| 2016-05 | [Free Programming Books][]   | 0    | [Create data science section and add Kaggle to it](https://github.com/vhf/free-programming-books/pull/1940)                                                                    |
| 2016-05 | [opengl-tutorial][]          | 0    | [Add empty line before triple quotes](https://github.com/opengl-tutorials/ogl/pull/18)                                                                                         |
| 2016-05 | [Bullet Physics][]           | 1    | [Improve HelloWorld](https://github.com/bulletphysics/bullet3/pull/612)                                                                                                        |
| 2016-04 | [freetype-gl][]              | 1    | [Find out how to compile on Ubuntu and document it](https://github.com/rougier/freetype-gl/pull/114)                                                                           |
| 2016-03 | [ranger][]                   | 0    | [gitignore install_log.txt generated by make install](https://github.com/hut/ranger/pull/506)                                                                                  |
| 2016-03 | [ranger][]                   | 1    | [Add %confdir macro](https://github.com/hut/ranger/pull/511)                                                                                                                   |
| 2016-03 | [ranger][]                   | 1    | [set_bookmark for directories other than the current](https://github.com/hut/ranger/pull/507)                                                                                  |
| 2016-02 | [ring.cx][]                  | 2    | [Create working Android video hardware decoding prototype](https://tuleap.ring.cx/plugins/tracker/?aid=446)                                                                    |
| 2016-02 | [ring.cx][]                  | 1    | [Started the one command build which was later made official](https://github.com/savoirfairelinux/ring-project)                                                                |
| 2016-01 | [leetcode][]                 | 1    | [java LRUCache with LinkedHashMap](https://github.com/haoel/leetcode/pull/90)                                                                                                  |
| 2015-12 | [Free Programming Books][]   | 0    | [Add InterviewBit to problem sets](https://github.com/vhf/free-programming-books/pull/1727)                                                                                    |
| 2015-10 | [linux-insides][]            | 0    | [Recommend ivandaviov/minimal to generate initrd](https://github.com/0xAX/linux-insides/pull/227)                                                                              |
| 2015-08 | [bare-metal-tetris][]        | 0    | [make clean also removes tetris.iso](https://github.com/programble/bare-metal-tetris/pull/2)                                                                                   |
| 2015-08 | [eduOS][]                    | 0    | [README typos Binutils and NASM](https://github.com/RWTH-OS/eduOS/pull/7)                                                                                                      |
| 2015-08 | [GDB][]                      | 0    | [python: fix Linetable case to LineTable in docstrings and comments](https://sourceware.org/ml/gdb-patches/2015-07/msg00744.html)                                              |
| 2015-07 | [GDB][]                      | 0    | [Remove outdated comment from call-rt-st.exp](https://sourceware.org/ml/gdb-patches/2015-08/msg00013.html)                                                                     |
| 2015-07 | [GDB][]                      | 0    | [Fix broken CONTRIBUTE link to GNU insignificant changes](https://sourceware.org/ml/gdb-patches/2015-08/msg00015.html)                                                         |
| 2015-07 | [GDB][]                      | 1    | [py-linetable.c: Fix doc of LineTable.source_lines' return type](https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;a=commit;h=7b849db4f213d6734b4121ca5e5cab3341a5140c) |
| 2015-07 | [Binutils][]                 | 1    | [Clarify case requirements for gas pseudo-ops](https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;a=commit;h=7e3023528162de7760a0e7e487aa81bbf44cb6a9)                   |
| 2015-07 | [Capstone][]                 | 0    | [Website typos at beyond_llvm](https://github.com/aquynh/capstone/issues/419)                                                                                                  |
| 2015-07 | [Vim Session][]              | 1    | [auto_save_to option added](https://github.com/xolox/vim-session/pull/81)                                                                                                      |
| 2015-05 | [NASM][]                     | 0    | [doc: typo occationally](https://bugzilla.nasm.us/show_bug.cgi?id=3392310)                                                                                                      |
| 2015-05 | [Free Programming Books][]   | 0    | [Computer Science from the Bottom Up](https://github.com/vhf/free-programming-books/pull/1468)                                                                                 |
| 2015-05 | [Free Programming Books][]   | 0    | [problem-sets: leetcode](https://github.com/vhf/free-programming-books/pull/1461)                                                                                              |
| 2015-05 | [Free Programming Books][]   | 0    | [Papers we love](https://github.com/vhf/free-programming-books/pull/1459)                                                                                                      |
| 2015-04 | [alternativeTo][]            | 0    | [icanprove.com](https://alternativeto.net/user/cirosantilli/added/)                                                                                                             |
| 2015-04 | [Free Programming Books][]   | 0    | [Knapsack Problems](https://github.com/vhf/free-programming-books/pull/1443)                                                                                                   |
| 2015-04 | [Free Programming Books][]   | 0    | [LSB](https://github.com/vhf/free-programming-books/pull/1442)                                                                                                                 |
| 2015-04 | [vim-snippets][]             | 0    | [java: prinlna to print array](https://github.com/honza/vim-snippets/pull/561)                                                                                                 |
| 2015-04 | [Free Programming Books][]   | 0    | [PEG Judge](https://wcipeg.com)                                                                                                                                                 |
| 2015-03 | [GitLab][]                   | 1    | [Convert many JavaScript # links to buttons](https://github.com/gitlabhq/gitlabhq/pull/7912)                                                                                   |
| 2015-03 | [GitLab][]                   | 1    | [Factor permission check in issuable finder](https://github.com/gitlabhq/gitlabhq/pull/8092)                                                                                   |
| 2015-03 | [Spring][]                   | 0    | [Typo Gardle -> Gradle](https://github.com/spring-projects/spring-integration-samples/pull/130)                                                                                |
| 2015-02 | [linux-insides][]            | 0    | [Make x86 paging reference title clearer](https://github.com/0xAX/linux-insides)                                                                                               |
| 2015-02 | [GitLab][]                   | 1    | [Ignore .bundle](https://github.com/gitlabhq/gitlab-shell/pull/184)                                                                                                            |
| 2015-02 | [Free programming books][]   | 0    | [Problem sets: CareerCup](https://github.com/vhf/free-programming-books/pull/1329)                                                                                             |
| 2015-01 | [vim-snippets][]             | 1    | [Fix false positive hyphen list item expansion](https://github.com/honza/vim-snippets/pull/511)                                                                                |
| 2015-01 | [GitLab][]                   | 1    | [Append in place for strings and arrays](https://github.com/gitlabhq/gitlabhq/pull/7999)                                                                                       |
| 2015-01 | [GitLab][]                   | 1    | [Remove unneeded password_confirmation from seed](https://github.com/gitlabhq/gitlabhq/pull/7878)                                                                              |
| 2015-01 | [GitLab][]                   | 0    | [Typo in project API events comment](https://github.com/gitlabhq/gitlabhq/pull/8307)                                                                                           |
| 2015-01 | [GitLab][]                   | 1    | [Replace match via get with get on routes](https://github.com/gitlabhq/gitlabhq/pull/7987)                                                                                     |
| 2015-01 | [GitLab][]                   | 0    | [Remove or prepend underscore _ to unused method arguments](https://github.com/gitlabhq/gitlabhq/pull/7925)                                                                    |
| 2015-01 | [GitLab][]                   | 1    | [Change always passing visible false tests](https://github.com/gitlabhq/gitlabhq/pull/7905)                                                                                    |
| 2015-01 | [GitLab][]                   | 1    | [Make blob new and edit file editors more uniform](https://github.com/gitlabhq/gitlabhq/pull/7951)                                                                             |
| 2015-01 | [GitLab][]                   | 1    | [Replace regex methods by string ones](https://github.com/gitlabhq/gitlabhq/pull/8096)                                                                                         |
| 2015-01 | [GitLab][]                   | 1    | [Simplify SSH fingerprint regexp extraction](https://github.com/gitlabhq/gitlabhq/pull/8430)                                                                                   |
| 2015-01 | [GitLab][]                   | 1    | [Add tests for disabled blob edit button cases v2](https://github.com/gitlabhq/gitlabhq/pull/8520)                                                                             |
| 2014-12 | [GitLab][]                   | 0    | [permission.md align table, rm double empty line](https://github.com/gitlabhq/gitlabhq/pull/8504)                                                                              |
| 2014-12 | [GitLab][]                   | 0    | [Remove commit indicator from path on Commits tab](https://github.com/gitlabhq/gitlabhq/pull/8324)                                                                             |
| 2014-12 | [GitLab][]                   | 0    | [Make protected branch perms explicit in doc](https://github.com/gitlabhq/gitlabhq/pull/8230)                                                                                  |
| 2014-12 | [GitLab][]                   | 0    | [doc workflow markdown style](https://github.com/gitlabhq/gitlabhq/pull/8497)                                                                                                  |
| 2014-12 | [GitLab][]                   | 1    | [Disallow POST to compare as it does not create objects](https://github.com/gitlabhq/gitlabhq/pull/7989)                                                                       |
| 2014-12 | [GitLab][]                   | 0    | [Sort .gitignore](https://github.com/gitlabhq/gitlabhq/pull/7782)                                                                                                              |
| 2014-12 | [GitLab][]                   | 1    | [Remove unused Project#code function](https://github.com/gitlabhq/gitlabhq/pull/7957)                                                                                          |
| 2014-12 | [GitLab][]                   | 0    | [Remove unused has_gitlab_shell3? method](https://github.com/gitlabhq/gitlabhq/pull/8256)                                                                                      |
| 2014-12 | [GitLab][]                   | 1    | [Add tests for tree edit routes](https://github.com/gitlabhq/gitlabhq/pull/7978)                                                                                               |
| 2014-12 | [GitLab][]                   | 1    | [Disable / hide MR edit blob button if cannot edit](https://github.com/gitlabhq/gitlabhq/pull/7886)                                                                            |
| 2014-12 | [GitLab][]                   | 0    | [Use blob local instead of instance](https://github.com/gitlabhq/gitlabhq/pull/7882)                                                                                           |
| 2014-12 | [GitLab][]                   | 1    | [Fix dev user seed: ID was used twice](https://github.com/gitlabhq/gitlabhq/pull/7894)                                                                                         |
| 2014-12 | [GitLab][]                   | 0    | [Fix Rake tasks doc README: add top level h1](https://github.com/gitlabhq/gitlabhq/pull/8466)                                                                                  |
| 2014-12 | [Ruby][]                     | 0    | [Typo close -> closes.](https://github.com/ruby/ruby/commit/512705e62d4929753845e449397cedeff0433f05)                                                                          |
| 2014-12 | [CommonMark][]               | 1    | [Add tests for normalize outer whitespace removal](https://github.com/jgm/CommonMark/pull/246)                                                                                 |
| 2014-12 | [CommonMark][]               | 1    | [spec_tests make --pattern affect --dump-tests](https://github.com/jgm/CommonMark/pull/249)                                                                                    |
| 2014-12 | [CommonMark][]               | 1    | [Add --number option to run a single test by its id](https://github.com/jgm/CommonMark/pull/247)                                                                               |
| 2014-12 | [CommonMark][]               | 1    | [Don't raise exception on invalid UTF-8 output](https://github.com/jgm/CommonMark/pull/250)                                                                                    |
| 2014-12 | [CommonMark][]               | 1    | [spec_tests add short options for common parameters](https://github.com/jgm/CommonMark/pull/248)                                                                               |
| 2014-12 | [CommonMark][]               | 0    | [Ignore pyc files](https://github.com/jgm/CommonMark/pull/240)                                                                                                                 |
| 2014-12 | [CommonMark][]               | 1    | [Expose failure to normalize whitespaces](https://github.com/jgm/CommonMark/pull/240)                                                                                          |
| 2014-11 | [vim-snippets][]             | 1    | [Markdown bold and italic](https://github.com/honza/vim-snippets/pull/488)                                                                                                     |
| 2014-11 | [vim-snippets][]             | 1    | [Markdown links URLs from the clipboard](https://github.com/honza/vim-snippets/pull/484)                                                                                       |
| 2014-11 | [vim-snippets][]             | 1    | [Markdown autolinks](https://github.com/honza/vim-snippets/pull/483)                                                                                                           |
| 2014-11 | [vim-snippets][]             | 1    | [Let the short version of links not have title.](https://github.com/honza/vim-snippets/pull/486)                                                                               |
| 2014-11 | [vim-snippets][]             | 1    | [Fix markdown fenced code blocks.](https://github.com/honza/vim-snippets/pull/487)                                                                                             |
| 2014-11 | [GitLab][]                   | 1    | [Delete tags and branches that start with hyphen](https://github.com/gitlabhq/gitlab-shell/pull/193)                                                                           |
| 2014-11 | [GitLab][]                   | 3    | [Restore hooks PATH before calling ruby](https://github.com/gitlabhq/gitlab-shell/pull/186)                                                                                    |
| 2014-11 | [GitLab][]                   | 1    | [Factor regex error messages with spec API tests](https://github.com/gitlabhq/gitlabhq/pull/8251)                                                                              |
| 2014-11 | [GitLab][]                   | 1    | [Move new blob commit message textarea below editor](https://github.com/gitlabhq/gitlabhq/pull/7944)                                                                           |
| 2014-11 | [gitbrute][]                 | 0    | [Usage](https://github.com/bradfitz/gitbrute/pull/4)                                                                                                                           |
| 2014-11 | [GitLab][]                   | 1    | [Factor GITLAB_SHELL_VERSION get method](https://github.com/gitlabhq/gitlabhq/pull/8254)                                                                                       |
| 2014-11 | [GitLab][]                   | 1    | [Create dev fixture projects with fixed visibility](https://github.com/gitlabhq/gitlabhq/pull/8168)                                                                            |
| 2014-11 | [GitLab][]                   | 1    | [Factor using Repository#path_to_repo](https://github.com/gitlabhq/gitlabhq/pull/8258)                                                                                         |
| 2014-11 | [GitLab][]                   | 1    | [Remove unused authenticate_user from project#show](https://github.com/gitlabhq/gitlabhq/pull/8094)                                                                            |
| 2014-11 | [GitLab][]                   | 1    | [Remove dead Event#new_branch? method](https://github.com/gitlabhq/gitlabhq/pull/8233)                                                                                         |
| 2014-11 | [GitLab][]                   | 1    | [Don't output to stdout from lib non-interactive methods](https://github.com/gitlabhq/gitlabhq/pull/8236)                                                                      |
| 2014-11 | [GitLab][]                   | 2    | [Fix version of test seed branches to specific revisions](https://github.com/gitlabhq/gitlabhq/pull/7903)                                                                      |
| 2014-11 | [GitLab][]                   | 1    | [Factor '0' * 40 blank ref constants](https://github.com/gitlabhq/gitlabhq/pull/8234)                                                                                          |
| 2014-11 | [GitLab][]                   | 1    | [Transform remove blob link into button](https://github.com/gitlabhq/gitlabhq/pull/7863)                                                                                       |
| 2014-11 | [GitLab][]                   | 1    | [Update default regex message to match regex](https://github.com/gitlabhq/gitlabhq/pull/7516)                                                                                  |
| 2014-11 | [GitLab][]                   | 0    | [Continue strings with backslash instead of append](https://github.com/gitlabhq/gitlabhq/pull/8222)                                                                            |
| 2014-11 | [GitLab][]                   | 1    | [Factor behaviors.scss constants](https://github.com/gitlabhq/gitlabhq/pull/8182)                                                                                              |
| 2014-11 | [GitLab][]                   | 0    | [Remove unneeded backslash: "\/" == "/"](https://github.com/gitlabhq/gitlabhq/pull/8241)                                                                                       |
| 2014-11 | [GitLab][]                   | 1    | [Fix push not allowed to protected branch if commit starts with 7 zeros](https://github.com/gitlabhq/gitlabhq/pull/8231)                                                       |
| 2014-11 | [GitLab][]                   | 1    | [Use require spec_helper instead of relative path](https://github.com/gitlabhq/gitlabhq/pull/8223)                                                                             |
| 2014-11 | [GitLab][]                   | 0    | [Fix doc rake import md style](https://github.com/gitlabhq/gitlabhq/pull/8211)                                                                                                 |
| 2014-11 | [GitLab][]                   | 1    | [Factor lib backend gitlab shell path](https://github.com/gitlabhq/gitlabhq/pull/8213)                                                                                         |
| 2014-10 | [GitLab][]                   | 1    | [Run user select Js only where needed](https://github.com/gitlabhq/gitlabhq/pull/8127)                                                                                         |
| 2014-10 | [GitLab][]                   | 1    | [Use button type=submit instead of input](https://github.com/gitlabhq/gitlabhq/pull/7866)                                                                                      |
| 2014-10 | [GitLab][]                   | 1    | [Only run profile js on pages that need it](https://github.com/gitlabhq/gitlabhq/pull/8120)                                                                                    |
| 2014-10 | [GitLab][]                   | 1    | [Better js -> URL projects map to reduce unneeded execution](https://github.com/gitlabhq/gitlabhq/pull/8123)                                                                   |
| 2014-10 | [GitLab][]                   | 1    | [Use Gitlab.config instead of Settings everywhere](https://github.com/gitlabhq/gitlabhq/pull/8005)                                                                             |
| 2014-10 | [GitLab][]                   | 1    | [Show nothing instead of unassigned on issues](https://github.com/gitlabhq/gitlabhq/pull/8155)                                                                                 |
| 2014-10 | [GitLab][]                   | 1    | [Only run namespace select js when needed](https://github.com/gitlabhq/gitlabhq/pull/8125)                                                                                     |
| 2014-10 | [GitLab][]                   | 0    | [Merge File basename and dirname into split](https://github.com/gitlabhq/gitlabhq/pull/8158)                                                                                   |
| 2014-10 | [GitLab][]                   | 1    | [Fix import.rake failed import if project name is also an existing namespace](https://github.com/gitlabhq/gitlabhq/pull/8159)                                                  |
| 2014-10 | [GitLab][]                   | 0    | [Remove unused variable user at lib/gitlab/markdown](https://github.com/gitlabhq/gitlabhq/pull/8150)                                                                           |
| 2014-10 | [GitLab][]                   | 1    | [Use argument list for sh instead of string](https://github.com/gitlabhq/gitlabhq/pull/8088)                                                                                   |
| 2014-10 | [GitLab][]                   | 1    | [Only run avatar chooser Js on pages that need it](https://github.com/gitlabhq/gitlabhq/pull/8114)                                                                             |
| 2014-10 | [GitLab][]                   | 1    | [Remove whitespace link between user group avatars](https://github.com/gitlabhq/gitlabhq/pull/8118)                                                                            |
| 2014-10 | [GitLab][]                   | 0    | [Fix doc raketasts import md style](https://github.com/gitlabhq/gitlabhq/pull/8139)                                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Remove unneeded app/finders config.autoload path](https://github.com/gitlabhq/gitlabhq/pull/7994)                                                                             |
| 2014-10 | [GitLab][]                   | 0    | [Improve grack auth hooks comment.](https://github.com/gitlabhq/gitlabhq/pull/8117)                                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Remove unused admin/projects#repository method](https://github.com/gitlabhq/gitlabhq/pull/8093)                                                                               |
| 2014-10 | [GitLab][]                   | 1    | [Factor admin logs](https://github.com/gitlabhq/gitlabhq/pull/7961)                                                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Remove unused filter from ProjectsController](https://github.com/gitlabhq/gitlabhq/pull/8029)                                                                                 |
| 2014-10 | [GitLab][]                   | 1    | [Remove unused dev_tools helper.](https://github.com/gitlabhq/gitlabhq/pull/8028)                                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Factor authorize_push! and authorize_code_access!](https://github.com/gitlabhq/gitlabhq/pull/8030)                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Replace match with end_with: more readable, faster](https://github.com/gitlabhq/gitlabhq/pull/8087)                                                                           |
| 2014-10 | [GitLab][]                   | 1    | [Use @project on controllers, don't call method](https://github.com/gitlabhq/gitlabhq/pull/8102)                                                                               |
| 2014-10 | [GitLab][]                   | 1    | [Remove param[:project_id] at admin controller](https://github.com/gitlabhq/gitlabhq/pull/8101)                                                                                |
| 2014-10 | [GitLab][]                   | 1    | [DRY mentioned in magic note constant](https://github.com/gitlabhq/gitlabhq/pull/8097)                                                                                         |
| 2014-10 | [GitLab][]                   | 1    | [Factor group forms](https://github.com/gitlabhq/gitlabhq/pull/8113)                                                                                                           |
| 2014-10 | [GitLab][]                   | 1    | [State on CONTRIBUTING that people should fix line style of touched lines](https://github.com/gitlabhq/gitlabhq/pull/8109)                                                     |
| 2014-10 | [GitLab][]                   | 1    | [Export all coffee classes with @](https://github.com/gitlabhq/gitlabhq/pull/8110)                                                                                             |
| 2014-10 | [GitLab][]                   | 1    | [Fix missing flash on file edit error from web UI.](https://github.com/gitlabhq/gitlabhq/pull/7856)                                                                            |
| 2014-10 | [Capybara][]                 | 0    | [Fix History typo.](https://github.com/jnicklas/capybara/pull/1424)                                                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Make new and edit file submit more uniform](https://github.com/gitlabhq/gitlabhq/pull/7942)                                                                                   |
| 2014-10 | [libgit2][]                  | 1    | [Join typedef and struct definitions in single file](https://github.com/libgit2/libgit2)                                                                                       |
| 2014-10 | [GitLab][]                   | 1    | [Factor dashboard helper methods](https://github.com/gitlabhq/gitlabhq/pull/7938)                                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Factor issue and merge request services](https://github.com/gitlabhq/gitlabhq/pull/7983)                                                                                      |
| 2014-10 | [GitLab][]                   | 1    | [Replace www.gitlab.com with about.gitlab.com](https://github.com/gitlabhq/gitlabhq/pull/7981)                                                                                 |
| 2014-10 | [GitLab][]                   | 0    | [Improve formatting of app/finders/README.md](https://github.com/gitlabhq/gitlabhq/pull/7991)                                                                                  |
| 2014-10 | [GitLab][]                   | 0    | [Remove outdated comment from commits_controller](https://github.com/gitlabhq/gitlabhq/pull/7985)                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Factor markup? gitlab_markdown? into new method](https://github.com/gitlabhq/gitlabhq/pull/7963)                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Remove unused title parameter](https://github.com/gitlabhq/gitlabhq/pull/7379)                                                                                                |
| 2014-10 | [GitLab][]                   | 1    | [Make Spinach test names consistent](https://github.com/gitlabhq/gitlabhq/pull/7940)                                                                                           |
| 2014-10 | [GitLab][]                   | 0    | [Ignore .bundle](https://github.com/gitlabhq/gitlab-shell/pull/184)                                                                                                            |
| 2014-10 | [GitLab][]                   | 0    | [Ignore tags file](https://github.com/gitlabhq/gitlab-shell/pull/183)                                                                                                          |
| 2014-10 | [GitLab][]                   | 0    | [Split one instance variable per line](https://github.com/gitlabhq/gitlab-shell/pull/182)                                                                                      |
| 2014-10 | [GitLab][]                   | 1    | [Factor commit message textareas](https://github.com/gitlabhq/gitlabhq/pull/7919)                                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Remove outdated comment on the project test seed](https://github.com/gitlabhq/gitlabhq/pull/7948)                                                                             |
| 2014-10 | [GitLab][]                   | 0    | [Remove assignment without effect.](https://github.com/gitlabhq/gitlabhq/pull/7947)                                                                                            |
| 2014-10 | [GitLab][]                   | 1    | [Add parenthesis to function def with arguments.](https://github.com/gitlabhq/gitlabhq/pull/7858)                                                                              |
| 2014-10 | [GitLab][]                   | 1    | [Remove test line without effect because no should.](https://github.com/gitlabhq/gitlabhq/pull/7834)                                                                           |
| 2014-10 | [GitLab][]                   | 1    | [Improve remove file commit message textarea placeholder](https://github.com/gitlabhq/gitlabhq/pull/7922)                                                                      |
| 2014-10 | [GitLab][]                   | 1    | [Replace :erb filter with plain HAML](https://github.com/gitlabhq/gitlabhq/pull/7880)                                                                                          |
| 2014-10 | [GitLab][]                   | 1    | [Remove blame lines added leading whitespace](https://github.com/gitlabhq/gitlabhq/pull/7881)                                                                                  |
| 2014-10 | [GitLab][]                   | 1    | [Improve new file commit message textarea placeholder.](https://github.com/gitlabhq/gitlabhq/pull/7921)                                                                        |
| 2014-10 | [GitLab][]                   | 1    | [Simplify custom MR good commit message hint](https://github.com/gitlabhq/gitlabhq/pull/7920)                                                                                  |
| 2014-10 | [GitLab][]                   | 1    | [Move group feature step to match test location](https://github.com/gitlabhq/gitlabhq/pull/7930)                                                                               |
| 2014-10 | [GitLab][]                   | 1    | [Titleize blob action buttons.](https://github.com/gitlabhq/gitlabhq/pull/7904)                                                                                                |
| 2014-09 | [GitLab][]                   | 0    | [Remove statement without effect.](https://github.com/gitlabhq/gitlabhq/pull/7914)                                                                                             |
| 2014-09 | [GitLab][]                   | 0    | [Fix dev merge seed: update testme to gitlab-test.](https://github.com/gitlabhq/gitlabhq/pull/7913)                                                                            |
| 2014-09 | [GitLab][]                   | 0    | [Remove trailing whitespace from views.](https://github.com/gitlabhq/gitlabhq/pull/7911)                                                                                       |
| 2014-09 | [GitLab][]                   | 1    | [Remove def project from tests that inherit it.](https://github.com/gitlabhq/gitlabhq/pull/7889)                                                                               |
| 2014-09 | [GitLab][]                   | 1    | [Replace testme with gitlab-test.](https://github.com/gitlabhq/gitlabhq/pull/7873)                                                                                             |
| 2014-09 | [GitLab][]                   | 1    | [Add predictable merge requests on dev seed.](https://github.com/gitlabhq/gitlabhq/pull/7897)                                                                                  |
| 2014-09 | [GitLab][]                   | 1    | [Prevent email sending on admin dev seed.](https://github.com/gitlabhq/gitlabhq/pull/7895)                                                                                     |
| 2014-09 | [GitLab][]                   | 1    | [Only show text wrap and diff notes for text in merge requests.](https://github.com/gitlabhq/gitlabhq/pull/7898)                                                               |
| 2014-09 | [GitLab][]                   | 1    | [Add web UI file CRUD tests.](https://github.com/gitlabhq/gitlabhq/pull/7862)                                                                                                  |
| 2014-09 | [GitLab][]                   | 1    | [Remove type submit from button_tag since default.](https://github.com/gitlabhq/gitlabhq/pull/7864)                                                                            |
| 2014-09 | [GitLab][]                   | 1    | [Replace empty? nil? with blank?.](https://github.com/gitlabhq/gitlabhq/pull/7877)                                                                                             |
| 2014-09 | [GitLab][]                   | 0    | [Typo indiciated -> indicated.](https://github.com/gitlabhq/gitlabhq/pull/7875)                                                                                                |
| 2014-09 | [GitLab][]                   | 1    | [Remove unnecessary page. from tests.](https://github.com/gitlabhq/gitlabhq/pull/7835)                                                                                         |
| 2014-09 | [GitLab][]                   | 1    | [Remove ununsed CONTRIBUTING link on edit MR form.](https://github.com/gitlabhq/gitlabhq/pull/7803)                                                                            |
| 2014-09 | [GitLab][]                   | 1    | [Add g++ dependency to ubuntu install.](https://gitlab.com/gitlab-org/gitlab-development-kit/merge_requests/22)                                                                |
| 2014-09 | [GitLab][]                   | 0    | [Hound prefer single quotes.](https://github.com/gitlabhq/gitlab_git/pull/44)                                                                                                  |
| 2014-09 | [libgit2][]                  | 0    | [Remove unused buf variable from path/core test.](https://github.com/libgit2/libgit2/pull/2570)                                                                                |
| 2014-09 | [GitLab][]                   | 1    | [Only clone GitLab Shell on tests if necessary.](https://github.com/gitlabhq/gitlabhq/pull/7823)                                                                               |
| 2014-09 | [GitLab][]                   | 1    | [Factor fork button view.](https://github.com/gitlabhq/gitlabhq/pull/7816)                                                                                                     |
| 2014-09 | [GitLab][]                   | 1    | [evaluate -> execute_script when return not needed.](https://github.com/gitlabhq/gitlabhq/pull/7838)                                                                           |
| 2014-09 | [GitLab][]                   | 1    | [evaluate_script history -> go_back and go_forward.](https://github.com/gitlabhq/gitlabhq/pull/7837)                                                                           |
| 2014-09 | [GitLab][]                   | 1    | [Factor current_url + URI.path into current_path.](https://github.com/gitlabhq/gitlabhq/pull/7833)                                                                             |
| 2014-09 | [GitLab][]                   | 1    | [Replace javascript:; links with buttons.](https://github.com/gitlabhq/gitlabhq/pull/7793)                                                                                     |
| 2014-09 | [GitLab][]                   | 1    | [Factor .add-diff-note active state.](https://github.com/gitlabhq/gitlabhq/pull/7795)                                                                                          |
| 2014-09 | [GitLab][]                   | 1    | [Fix link_to_reply_diff.](https://github.com/gitlabhq/gitlabhq/pull/7792)                                                                                                      |
| 2014-09 | [GitLab][]                   | 1    | [Factor issue and MR edit form error list.](https://github.com/gitlabhq/gitlabhq/pull/7804)                                                                                    |
| 2014-09 | [GitLab][]                   | 1    | [Factor error and success methods from services.](https://github.com/gitlabhq/gitlabhq/pull/7807)                                                                              |
| 2014-09 | [GitLab][]                   | 1    | [Set textarea resize:vertical by default.](https://github.com/gitlabhq/gitlabhq/pull/7772)                                                                                     |
| 2014-09 | [GitLab][]                   | 1    | [Factor out commit list from compare and new MR.](https://github.com/gitlabhq/gitlabhq/pull/7657)                                                                              |
| 2014-09 | [GitLab][]                   | 1    | [Prefix Spinach features with Spinach::Features::.](https://github.com/gitlabhq/gitlabhq/pull/7821)                                                                            |
| 2014-09 | [GitLab][]                   | 0    | [Typo it -> its.](https://github.com/gitlabhq/gitlabhq/pull/7814)                                                                                                              |
| 2014-09 | [GitLab][]                   | 1    | [Factor zen mode.](https://github.com/gitlabhq/gitlabhq/pull/7801)                                                                                                             |
| 2014-09 | [GitLab][]                   | 0    | [Ignore tags file.](https://github.com/gitlabhq/gitlabhq/pull/7771)                                                                                                            |
| 2014-09 | [GitLab][]                   | 1    | [Improve zen mode internals.](https://github.com/gitlabhq/gitlabhq/pull/7797)                                                                                                  |
| 2014-09 | [GitLab][]                   | 0    | [CONTRIBUTING typos.](https://github.com/gitlabhq/gitlabhq/pull/7791)                                                                                                          |
| 2014-09 | [Marked][]                   | 1    | [Add browser usage to README](https://github.com/chjj/marked/pull/414)                                                                                                         |
| 2014-09 | [GitLab][]                   | 0    | [Typo herlper -> helper.](https://github.com/gitlabhq/gitlab_git/pull/43)                                                                                                      |
| 2014-09 | [libgit2][]                  | 1    | [Factor 40 and 41 constants from source.](https://github.com/libgit2/libgit2/pull/2567)                                                                                        |
| 2014-09 | [libgit2][]                  | 1    | [Replace void casts with GIT_UNUSED.](https://github.com/libgit2/libgit2/pull/2572)                                                                                            |
| 2014-09 | [Rugged][]                   | 0    | [Typo "di ff" -> diff.](https://github.com/libgit2/rugged/pull/419)                                                                                                            |
| 2014-09 | [Rugged][]                   | 0    | [Remove trailing whitespace.](https://github.com/libgit2/rugged/pull/417)                                                                                                      |
| 2014-09 | [Rugged][]                   | 0    | [Gitignore rdoc/.](https://github.com/libgit2/rugged/pull/416)                                                                                                                 |
| 2014-09 | [Rugged][]                   | 0    | [Factor File.join in test sandbox_init.](https://github.com/libgit2/rugged/pull/415)                                                                                           |
| 2014-09 | [Rails][]                    | 1    | [Explain ERB space removal.](https://github.com/rails/rails/pull/16790)                                                                                                        |
| 2014-09 | [GitLab][]                   | 0    | [Update README to match Md style in CONTRIBUTING.](https://github.com/gitlabhq/gitlab_git/pull/39)                                                                             |
| 2014-09 | [GitLab][]                   | 0    | [Typo localy -> locally](https://github.com/gitlabhq/gitlabhq/pull/7726)                                                                                                       |
| 2014-09 | [vader.vim][]                | 1    | [Add run-tests script.](https://github.com/junegunn/vader.vim/pull/16)                                                                                                         |
| 2014-09 | [vader.vim][]                | 2    | [Add SyntaxAt and SyntaxOf helpers.](https://github.com/junegunn/vader.vim/pull/22)                                                                                            |
| 2014-09 | [Rugged][]                   | 0    | [Remove trailing whitespace.](https://github.com/libgit2/rugged/pull/417)                                                                                                      |
| 2014-09 | [Rugged][]                   | 0    | [Gitignore rdoc/.](https://github.com/libgit2/rugged/pull/416)                                                                                                                 |
| 2014-09 | [Rugged][]                   | 0    | [Factor File.join in test sandbox_init.](https://github.com/libgit2/rugged/pull/415)                                                                                           |
| 2014-09 | [Pro Git book][]             | 1    | [Mention packed-refs.](https://github.com/progit/progit/pull/878)                                                                                                              |
| 2014-09 | [GitLab][]                   | 1    | [Add link to fixed SHA version on blob.](https://github.com/gitlabhq/gitlabhq/pull/7472)                                                                                       |
| 2014-09 | [GitLab][]                   | 1    | [Factor new issue and edit MR forms.](https://github.com/gitlabhq/gitlabhq/pull/7678)                                                                                          |
| 2014-09 | [GitLab][]                   | 1    | [Fix missing to on reassign Merge Request text email to unassigned.](https://github.com/gitlabhq/gitlabhq/pull/7677)                                                           |
| 2014-09 | [GitLab][]                   | 1    | [Fix missing to on reassign Merge Request email to unassigned.](https://github.com/gitlabhq/gitlabhq/pull/7661)                                                                |
| 2014-09 | [Markdown Test Suite][]      | 1    | [Run multimarkdown in compatibility mode.](https://github.com/karlcow/markdown-testsuite/pull/60)                                                                              |
| 2014-09 | [Markdown Test Suite][]      | 1    | [Link to stmd.](https://github.com/karlcow/markdown-testsuite/pull/69)                                                                                                         |
| 2014-09 | [GitLab][]                   | 1    | [Add users with deterministic username and password to development seed.](https://github.com/gitlabhq/gitlabhq/pull/7211)                                                      |
| 2014-09 | [Rails][]                    | 0    | [Shorten ActionView::Base doc summary line.](https://github.com/rails/rails/pull/16774)                                                                                        |
| 2014-09 | [Rails][]                    | 1    | [Clarify Rails uses erubis not stdlin ERB.](https://github.com/rails/rails/pull/16773)                                                                                         |
| 2014-08 | [vim-snippets][]             | 1    | [Rename node p to pipe](https://github.com/honza/vim-snippets/pull/432)                                                                                                        |
| 2014-08 | [GitLab][]                   | 0    | [Typo.](https://github.com/gitlabhq/gitlabhq/pull/7641)                                                                                                                        |
| 2014-08 | [vim-snippets][]             | 1    | [README improvements: md style, typos, fix links.](https://github.com/honza/vim-snippets/pull/431)                                                                             |
| 2014-08 | [vim-snippets][]             | 1    | [Add tex hyperlink snippets.](https://github.com/honza/vim-snippets/pull/429)                                                                                                  |
| 2014-08 | [GitLab][]                   | 1    | [Remove HAML eval for const strings.](https://github.com/gitlabhq/gitlabhq/pull/7609)                                                                                          |
| 2014-08 | [Softcover][]                | 1    | [Ignore template top level tex file.](https://github.com/softcover/softcover/pull/116)                                                                                         |
| 2014-08 | [Softcover][]                | 1    | [Fix failing PDF fontsize verbatim test.](https://github.com/softcover/softcover/pull/103)                                                                                     |
| 2014-08 | [vim-snippets][]             | 1    | [Add tex listings snippets.](https://github.com/honza/vim-snippets/pull/422)                                                                                                   |
| 2014-08 | [GitLab][]                   | 0    | [Fix Md style for API docs.](https://github.com/gitlabhq/gitlabhq/pull/7509)                                                                                                   |
| 2014-08 | [GitLab][]                   | 0    | [Fix Md style for projects API doc.](https://github.com/gitlabhq/gitlabhq/pull/7508)                                                                                           |
| 2014-08 | [GitLab][]                   | 1    | [Restrict commit area resize to vertical.](https://github.com/gitlabhq/gitlabhq/pull/7483)                                                                                     |
| 2014-08 | [GitLab][]                   | 0    | [Update README Markdown style to match CONTRIBUTING](https://github.com/gitlabhq/gitlab-shell/pull/169)                                                                        |
| 2014-07 | [Pro Git book][]             | 1    | [Set dummy merge driver merge ours .gitattributes.](https://github.com/progit/progit/pull/751)                                                                                 |
| 2014-07 | [GitLab][]                   | 2    | [Add project stars.](https://github.com/gitlabhq/gitlabhq/pull/7233)                                                                                                           |
| 2014-07 | [GitLab][]                   | 1    | [Increase diff byte highlight contrast.](https://github.com/gitlabhq/gitlabhq/pull/7340)                                                                                       |
| 2014-07 | [GitLab][]                   | 0    | [Clarify squash comes after review.](https://github.com/gitlabhq/gitlabhq/pull/7257)                                                                                           |
| 2014-07 | [GitLab][]                   | 0    | [Enforce Markdown style.](https://github.com/gitlabhq/gitlabhq/pull/7196)                                                                                                      |
| 2014-07 | [Octokat.js][]               | 1    | [Gitignore fixtures and dist/commonjs.](https://github.com/philschatz/octokat.js/pull/7/files)                                                                                 |
| 2014-07 | [GitLab][]                   | 1    | [Fix username validation message to match regexp.](https://github.com/gitlabhq/gitlabhq/pull/7204)                                                                             |
| 2014-06 | [GitLab][]                   | 1    | [Add trailing newline to all text files.](https://github.com/gitlabhq/gitlabhq/pull/7170)                                                                                      |
| 2014-06 | [GitLab][]                   | 0    | [Typo.](https://github.com/gitlabhq/gitlabhq/pull/7195)                                                                                                                        |
| 2014-06 | [Markdown Lint][]            | 0    | [Typo.](https://github.com/mivok/markdownlint/pull/1)                                                                                                                          |
| 2014-06 | [Rails][]                    | 0    | [Typo.](https://github.com/rails/rails/pull/15997)                                                                                                                             |
| 2014-06 | [GitLab][]                   | 1    | [Replace HTML5 obsolete center element with CSS.](https://github.com/gitlabhq/gitlabhq/pull/7169)                                                                              |
| 2014-06 | [developper.github.com][]    | 1    | [Explain :user is username not ID.](https://github.com/github/developer.github.com/pull/543)                                                                                   |
| 2014-06 | [Prose][]                    | 0    | [Correct CONTRIBUTING typos.](https://github.com/prose/prose/pull/724)                                                                                                         |
| 2014-06 | [Octokat.js][]               | 1    | [Fix `repo` to `repos` in README examples.](https://github.com/philschatz/octokat.js/pull/5)                                                                                   |
| 2014-06 | [Octokat.js][]               | 1    | [Fix typos and style on README.](https://github.com/philschatz/octokat.js/pull/6)                                                                                              |
| 2014-06 | [octokit.js][]               | 0    | [Remove trailing whitespace.](https://github.com/philschatz/octokit.js/pull/57)                                                                                                |
| 2014-06 | [octokit.js][]               | 1    | [Add grunt watch.](https://github.com/philschatz/octokit.js/pull/56)                                                                                                           |
| 2014-06 | [Octokat.js][]               | 0    | [Remove unneeded semicolon.](https://github.com/philschatz/octokat.js/pull/3)                                                                                                  |
| 2014-06 | [Octokat.js][]               | 1    | [Add grunt watch.](https://github.com/philschatz/octokat.js/pull/2)                                                                                                            |
| 2014-06 | [Markdown Test Suite][]      | 2    | [Add Vagrantfile.](https://github.com/karlcow/markdown-testsuite/pull/55)                                                                                                      |
| 2014-06 | [Markdown Test Suite][]      | 1    | [Remove hoedown options.](https://github.com/karlcow/markdown-testsuite/pull/54)                                                                                               |
| 2014-06 | [vim-snippets][]             | 1    | [Add HTML `ac` Anchor from Clipboard.](https://github.com/honza/vim-snippets/pull/386)                                                                                         |
| 2014-06 | [RVM][]                      | 0    | [Correct some doc typos.](https://github.com/wayneeseguin/rvm/pull/2900)                                                                                                       |
| 2014-06 | [GitLab][]                   | 1    | [Clarify that bbastov is the style of Hound CI.](https://github.com/gitlabhq/gitlabhq/pull/7107)                                                                               |
| 2014-06 | [GitLab][]                   | 2    | [Update docs to match new markdown style guide.](https://github.com/gitlabhq/gitlabhq/pull/6863)                                                                               |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add blackfriday, lunamark, maruku and rdiscount.](https://github.com/karlcow/markdown-testsuite/pull/51)                                                                      |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add autolink-no-bracket extension test.](https://github.com/karlcow/markdown-testsuite/pull/44)                                                                               |
| 2014-05 | [Markdown Test Suite][]      | 0    | [Add showdown engine.](https://github.com/karlcow/markdown-testsuite/pull/45)                                                                                                  |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Title attribute is significant at normalization.](https://github.com/karlcow/markdown-testsuite/pull/47)                                                                      |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add design goals.](https://github.com/karlcow/markdown-testsuite/pull/48)                                                                                                     |
| 2014-05 | [Markdown Test Suite][]      | 0    | [Add Python Markdown 2 engine.](https://github.com/karlcow/markdown-testsuite/pull/49)                                                                                         |
| 2014-05 | [Markdown Test Suite][]      | 0    | [Add peg-markdown engine.](https://github.com/karlcow/markdown-testsuite/pull/50)                                                                                              |
| 2014-05 | [GitLab][]                   | 1    | [Commit message textareas have 72 char mark line.](https://github.com/gitlabhq/gitlabhq/pull/6385)                                                                             |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add autolink-no-bracket extension test.](https://github.com/karlcow/markdown-testsuite/pull/44)                                                                               |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add link-idref-implicit-no-bracket test.](https://github.com/karlcow/markdown-testsuite/pull/43)                                                                              |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Minor fixes to addition of hoedown.](https://github.com/karlcow/markdown-testsuite/pull/42)                                                                                   |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Remove no-auto-id argument for kramdown.](https://github.com/karlcow/markdown-testsuite/pull/41)                                                                              |
| 2014-05 | [Markdown Test Suite][]      | 1    | [Add markdown_pl Markdown.pl engine.](https://github.com/karlcow/markdown-testsuite/pull/36)                                                                                   |
| 2014-04 | [GitLab][]                   | 0    | [Remove redundant signin link from signin page.](https://github.com/gitlabhq/gitlabhq/pull/6892)                                                                               |
| 2014-04 | [GitLab][]                   | 1    | [Add help link to header.](https://github.com/gitlabhq/gitlabhq/pull/6897)                                                                                                     |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Improve output normalization with custom parser.](https://github.com/karlcow/markdown-testsuite/pull/31)                                                                      |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Add ordered-list-inner-par-list test.](https://github.com/karlcow/markdown-testsuite/pull/40)                                                                                 |
| 2014-04 | [GitLab CI][]                | 1    | [Add application.yml.example.development.](https://github.com/gitlabhq/gitlab-ci/pull/422)                                                                                     |
| 2014-04 | [Boost Graph][]              | 1    | [Explicitly use vertex type on quick tour example.](https://github.com/boostorg/graph/pull/8)                                                                                  |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Add list-code-1-space test.](https://github.com/karlcow/markdown-testsuite/pull/34)                                                                                           |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Add md2html engine.](https://github.com/karlcow/markdown-testsuite/pull/33)                                                                                                   |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Remove email tests because output is random.](https://github.com/karlcow/markdown-testsuite/pull/32)                                                                          |
| 2014-04 | [Markdown Test Suite][]      | 2    | [Run only tests that contain string in title.](https://github.com/karlcow/markdown-testsuite/pull/30)                                                                          |
| 2014-04 | [Markdown Test Suite][]      | 1    | [Add marked engine.](https://github.com/karlcow/markdown-testsuite/pull/29)                                                                                                    |
| 2014-04 | [GitLab][]                   | 1    | [Add markdown styleguide.](https://github.com/gitlabhq/gitlabhq/pull/6795)                                                                                                     |
| 2014-04 | [GitLab][]                   | 1    | [Include SASS in subdirectories with glob.](https://github.com/gitlabhq/gitlabhq/pull/6775)                                                                                    |
| 2014-04 | [Tig][]                      | 1    | [Add refs bind `!` to delete branch.](https://github.com/jonas/tig/pull/270)                                                                                                   |
| 2014-04 | [GitLab][]                   | 1    | [Rename issue form tags to match MR and params.](https://github.com/gitlabhq/gitlabhq/pull/6774)                                                                               |
| 2014-04 | [GitLab][]                   | 1    | [Say issues are accepted at both GitLab and GitHub.](https://github.com/gitlabhq/gitlabhq/pull/6749)                                                                           |
| 2014-03 | [Markdown Test Suite][]      | 1    | [Document config_local.py on README.](https://github.com/karlcow/markdown-testsuite/pull/23)                                                                                   |
| 2014-03 | [Markdown Test Suite][]      | 1    | [Factor out engines that are commands on PATH.](https://github.com/karlcow/markdown-testsuite/pull/24)                                                                         |
| 2014-03 | [Markdown Test Suite][]      | 1    | [Add sample run-tests.py output to README.](https://github.com/karlcow/markdown-testsuite/pull/25)                                                                             |
| 2014-03 | [Markdown Test Suite][]      | 1    | [Check if are no engines enabled to avoid exception.](https://github.com/karlcow/markdown-testsuite/pull/26)                                                                   |
| 2014-03 | [Vim Markdown][]             | 1    | [Add Toc commands.](https://github.com/plasticboy/vim-markdown/pull/71)                                                                                                        |
| 2014-03 | [Markdown Test Suite][]      | 0    | [One disable per line commented out on conf.](https://github.com/karlcow/markdown-testsuite/pull/21)                                                                           |
| 2014-03 | [Markdown Test Suite][]      | 0    | [Add multimarkdown support.](https://github.com/karlcow/markdown-testsuite/pull/20)                                                                                            |
| 2014-03 | [Markdown Test Suite][]      | 0    | [Typo conten -> content.](https://github.com/karlcow/markdown-testsuite/pull/18)                                                                                               |
| 2014-03 | [Markdown Test Suite][]      | 2    | [Automated tests.](https://github.com/karlcow/markdown-testsuite/pull/15)                                                                                                      |
| 2014-03 | [GitLab CI][]                | 0    | [Remove config/puma.rb from gitignore.](https://github.com/gitlabhq/gitlab-ci/pull/405)                                                                                        |
| 2014-03 | [GitLab CI][]                | 0    | [Ignore config/unicorn.rb.](https://github.com/gitlabhq/gitlab-ci/pull/404)                                                                                                    |
| 2014-03 | [GitLab CI][]                | 0    | [Tell users to install bundle locally without sudo.](https://github.com/gitlabhq/gitlab-ci-runner/pull/79)                                                                     |
| 2014-03 | [GitLab CI][]                | 0    | [Document where to find the registration token.](https://github.com/gitlabhq/gitlab-ci-runner/pull/78)                                                                         |
| 2014-03 | [Markdown Test Suite][]      | 0    | [Remove space from simple list, specify asterisk.](https://github.com/karlcow/markdown-testsuite/pull/14)                                                                      |
| 2014-03 | [Markdown Test Suite][]      | 1    | [Add script to cat all input files.](https://github.com/karlcow/markdown-testsuite/pull/13)                                                                                    |
| 2014-03 | [Markdown Test Suite][]      | 0    | [Remove newline from empty files.](https://github.com/karlcow/markdown-testsuite/pull/12)                                                                                      |
| 2014-03 | [GitLab][]                   | 1    | [Start development Key seed id from 1.](https://github.com/gitlabhq/gitlabhq/pull/6601)                                                                                        |
| 2014-03 | [GitLab][]                   | 1    | [Show link to public projects for new users.](https://github.com/gitlabhq/gitlabhq/pull/6544)                                                                                  |
| 2014-03 | [GitLab Cookbook][]          | 1    | [Correct bindfs metal dev init script.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/57/diffs)                                                                 |
| 2014-03 | [GitLab CI][]                | 0    | [Organize gitignore.](https://github.com/gitlabhq/gitlab-ci/pull/391)                                                                                                          |
| 2014-03 | [GitLab Cookbook][]          | 1    | [Correct metal install home share technique.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/55)                                                                 |
| 2014-03 | [GitLab Cookbook][]          | 0    | [Uniform markdown headers](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/53)                                                                                    |
| 2014-03 | [GitLab Cookbook][]          | 0    | [Typo ommited -> omitted.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/54)                                                                                    |
| 2014-03 | [GitLab][]                   | 0    | [Documentation Typos](https://github.com/gitlabhq/gitlabhq/pull/6489)                                                                                                          |
| 2014-02 | [Vim Markdown][]             | 1    | [Add contributing guidelines and started tests as required by them.](https://github.com/plasticboy/vim-markdown/pull/60)                                                       |
| 2014-02 | [Vim Markdown][]             | 0    | [Add Vundle install to README, updated pathogen URL to GitHub.](https://github.com/plasticboy/vim-markdown/pull/61)                                                            |
| 2014-02 | [Vim Markdown][]             | 0    | [Create credits section, remove link to old homepage.](https://github.com/plasticboy/vim-markdown/pull/62)                                                                     |
| 2014-02 | [GitLab][]                   | 1    | [Remove dir prefix from filename of tests under dir.](https://github.com/gitlabhq/gitlabhq/pull/6386)                                                                          |
| 2014-02 | [Markdown Test Suite][]      | 0    | [Make title more readable.](https://github.com/karlcow/markdown-testsuite/pull/10)                                                                                             |
| 2014-02 | [Markdown Test Suite][]      | 0    | [Make readme intro more direct.](https://github.com/karlcow/markdown-testsuite/pull/9)                                                                                         |
| 2014-02 | [Markdown Test Suite][]      | 1    | [Add extensions.](https://github.com/karlcow/markdown-testsuite/pull/8)                                                                                                        |
| 2014-02 | [GitLab][]                   | 2    | [Blob and tree markdown links to anchors work.](https://github.com/gitlabhq/gitlabhq/pull/6375)                                                                                |
| 2014-02 | [git-browse-remote][]        | 0    | [Add install instructions.](https://github.com/motemen/git-browse-remote/pull/10)                                                                                              |
| 2014-02 | [ShareLaTeX][]               | 1    | [Remove latexmk install instructions from README.](https://github.com/sharelatex/sharelatex/pull/57)                                                                           |
| 2014-02 | [ShareLaTeX][]               | 1    | [Remove dollars from readme bash code.](https://github.com/sharelatex/sharelatex/pull/56)                                                                                      |
| 2014-02 | [ShareLaTeX][]               | 1    | [Add dummy version to package.json to fix install.](https://github.com/sharelatex/sharelatex/pull/53)                                                                          |
| 2014-02 | [ShareLaTeX][]               | 1    | [Add .nvmrc](https://github.com/sharelatex/sharelatex/pull/52)                                                                                                                 |
| 2014-02 | [GitLab][]                   | 2    | [User can leave group from group page.](https://github.com/gitlabhq/gitlabhq/pull/6274)                                                                                        |
| 2014-02 | [GitLab][]                   | 2    | [Add anchors to markdown rendered headers.](https://github.com/gitlabhq/gitlabhq/pull/6219)                                                                                    |
| 2014-02 | [GitLab][]                   | 2    | [User profile pages are publicly visible.](https://github.com/gitlabhq/gitlabhq/pull/6177)                                                                                     |
| 2014-01 | [GitLab Cookbook][]          | 1    | [Development install documentation correction.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/33)                                                               |
| 2014-01 | [GitLab Cookbook][]          | 2    | [Create metal development install documentation.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/29)                                                             |
| 2014-01 | [GitLab Cookbook][]          | 0    | [Improve docs.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/30)                                                                                               |
| 2014-01 | [GitLab Cookbook][]          | 1    | [Add option to control the SSH port used.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/23)                                                                    |
| 2013-12 | [GitLab Cookbook][]          | 1    | [Improve production install docs.](https://gitlab.com/gitlab-org/cookbook-gitlab/merge_requests/11)                                                                            |
| 2013-11 | [Vim Markdown][]             | 1    | [Header navigation mappings work for Setext headers.](https://github.com/plasticboy/vim-markdown/pull/52)                                                                      |
| 2013-10 | [Okular][]                   | 1    | [Add shortcut to Change Colors on a page.](https://git.reviewboard.kde.org/r/113434/)                                                                                          |
| 2013-09 | [Vim Markdown][]             | 2    | [Add mappings to navigate across headers.](https://github.com/plasticboy/vim-markdown/pull/37)                                                                                 |
| 2013-02 | [SciPy][]                    | 1    | [Improve documentation.](https://github.com/scipy/scipy/pull/365)                                                                                                              |
| 2013-01 | [Django Userena][]           | 1    | [Add new configuration option.](https://github.com/bread-and-pepper/django-userena/commit/6a0bc1575a1816a130644efde411fbed131720be)                                            |
| 2012-11 | [DataTables][]               | 1    | [Improved a doc example.](https://github.com/DataTables/DataTables/commits?author=cirosantilli)                                                                                |
{: .patches-table .data-table}

[Patches waiting for review](/projects-pending).

### Merged by me

Patches which were merged by myself on repositories which I feel have large public visibility, e.g. those to which I have been given push permission.

Repositories to which I gained push permission because of my contributions:

- <https://github.com/plasticboy/vim-markdown>

| Date    | Project          | Size | Description                                                                                                                                  |
|---------|------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------|
| 2017-07 | [BusyBox][]      | 1    | [dd status=none does nothing and still prints status](https://bugs.busybox.net/show_bug.cgi?id=10066)                                        |
| 2016-04 | [ranger][]       | 0    | [Make the :source command from actions.py part of the public API and document it in the man pages](https://github.com/hut/ranger/issues/510) |
| 2015-05 | [Vim Markdown][] | 0    | [Document `<Plug>Markdown_OpenUrlUnderCursor`](https://github.com/plasticboy/vim-markdown/pull/205)                                          |
| 2015-05 | [Vim Markdown][] | 0    | [Add TOC to README](https://github.com/plasticboy/vim-markdown/pull/193)                                                                     |
| 2015-05 | [Vim Markdown][] | 1    | [Allow users to disable individual maps with hasmapto checks](https://github.com/plasticboy/vim-markdown/pull/207)                           |
| 2015-04 | [Vim Markdown][] | 2    | [gx works from anywhere inside Markdown links](https://github.com/plasticboy/vim-markdown/pull/183)                                          |
| 2015-04 | [Vim Markdown][] | 0    | [Change the README h1 to "Vim Markdown"](https://github.com/plasticboy/vim-markdown/pull/177)                                                |
| 2015-04 | [Vim Markdown][] | 0    | [Improve README formatting](https://github.com/plasticboy/vim-markdown/pull/178)                                                             |
| 2014-10 | [Vim Markdown][] | 2    | [Highlight angle braced hyperlinks](https://github.com/plasticboy/vim-markdown/pull/121)                                                     |
| 2014-10 | [Vim Markdown][] | 0    | [Use a single code block style on README](https://github.com/plasticboy/vim-markdown/pull/134)                                               |
| 2014-10 | [Vim Markdown][] | 1    | [Improve bold and italic tests](https://github.com/plasticboy/vim-markdown/pull/133)                                                         |
| 2014-10 | [Vim Markdown][] | 0    | [Remove outdated fields from syntax header](https://github.com/plasticboy/vim-markdown/pull/132)                                             |
| 2014-09 | [Vim Markdown][] | 1    | [Support YAML frontmatter headers v2.](https://github.com/plasticboy/vim-markdown/pull/124)                                                  |
| 2014-09 | [Vim Markdown][] | 1    | [Add LaTeX \$ and \$\$ math support.](https://github.com/plasticboy/vim-markdown/pull/123)                                                   |
| 2014-09 | [Vim Markdown][] | 1    | [Add unit tests and travis support.](https://github.com/plasticboy/vim-markdown/pull/128)                                                    |
| 2014-09 | [Vim Markdown][] | 1    | [Fix parenthesis and square brackets that were rendered as links when not in link.](https://github.com/plasticboy/vim-markdown/pull/122)     |
| 2014-06 | [Vim Markdown][] | 1    | [Add commands to increase and decrease header levels.](https://github.com/plasticboy/vim-markdown/pull/88)                                   |
| 2014-03 | [Vim Markdown][] | 1    | [Use Markdown Test Suite for the tests wherever possible.](https://github.com/plasticboy/vim-markdown/pull/69)                               |
{: .patches-table .data-table}

## Bug reports and feature requests

- I opened and was confirmed or generated considerable interest
- I wrote comments pointing out a non obvious cause/fix/duplicate.
- I reviewed the patch

This shall not list bugs solved by my accepted pull requests.

### Closed source

Disclaimer: closed source vendors tend to be highly secretive, solving small issues without any reply, so I use my best judgement given the lack of feedback.

| Date    | Project                      | Type         | Description                                                                                                                                                |
|---------|------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2019-07 | https://zenodo.org/          | Security bug | [Cross-Site Scripting vulnerability](http://web.archive.org/web/20190715192018/http://blog.zenodo.org/2019/07/15/2019-07-15-xss-vulnerability/)            |
| 2015-09 | [GitHub][]                   | Support      | [Add ability to fork and edit files from external URL](https://github.com/isaacs/github/issues/460)                                                        |
| 2015-05 | [GitHub][]                   | Bug          | [500 when listing GCC mirror branches](https://github.com/isaacs/github/issues/398)                                                                        |
| 2015-04 | [Free Software Foundation][] | Bug          | [Duplicated paragraph at Octave at description of high priority projects](https://github.com/cirosantilli/issues/issues/3)                                 |
| 2015-03 | [GitHub][]                   | Bug          | [@about and @pricing generate at mentions even though they are reserved](https://github.com/isaacs/github/issues/375)                                      |
| 2015-03 | [Jenkov tutorials][]         | Typo         | [typo boolean -> long](http://tutorials.jenkov.com/java-util-concurrent/atomiclong.html)                                                                   |
| 2015-03 | [GitHub][]                   | Bug          | [502 on homepage on long streak](https://github.com/isaacs/github/issues/370)                                                                              |
| 2015-02 | [GitHub][]                   | Bug          | [If a CONTRIBUTING.md that is a symlink is present, the link to it should not show on new issue forms](https://github.com/isaacs/github/issues/348)        |
| 2015-02 | [GitHub][]                   | Feature      | [Allow to reopen pull requests after a force push](https://github.com/isaacs/github/issues/361)                                                            |
| 2015-02 | [GitHub][]                   | Bug          | [If a CONTRIBUTING.md that is a symlink is present, the link to it should not show on new issue forms](https://github.com/isaacs/github/issues/348)        |
| 2014-12 | [My Science Work][]          | Typo         | Typos on settings page                                                                                                                                     |
| 2014-12 | [GitHub][]                   | Bug          | [Merge pull request window appears after rebase even if I don't have permission](https://github.com/isaacs/github/issues/321)                              |
| 2014-12 | [GitHub][]                   | Feature      | [Repository Traffic Analytics API](https://github.com/isaacs/github/issues/320)                                                                            |
| 2014-12 | [GitHub][]                   | Support      | [Pin issues or add header text to issues page](https://github.com/isaacs/github/issues/315)                                                                |
| 2014-12 | [GitHub][]                   | Bug          | [Tree show links blobs to the last commit that contained the blob instead of commit that introduced the file](https://github.com/isaacs/github/issues/319) |
| 2014-12 | [GitHub][]                   | Duplicate    | [Deal properly with uppercase .GIT file basenames on web editor like for lowercase .git](https://github.com/isaacs/github/issues/318)                      |
| 2014-12 | [GitHub][]                   | Duplicate    | [Add a "I have this issue too" button](https://github.com/isaacs/github/issues/314)                                                                        |
| 2014-11 | [GitBook][]                  | Bug          | [500 on /edit without access](https://support.gitbook.com/hc/communities/public/questions/200628582-500-on-edit-without-access)                            |
| 2014-11 | [GitHub][]                   | Feature      | [View non-rendered markdown source with line numbers on blob show](https://github.com/isaacs/github/issues/297)                                            |
| 2014-11 | [GitHub][]                   | Bug          | [500 on branch index for long branch name pushed together with other branch](https://github.com/isaacs/github/issues/303)                                  |
| 2014-11 | [GitHub][]                   | Bug          | [GFM ordered list with inner unordered paragraph list generates two ordered lists](https://github.com/isaacs/github/issues/181#issuecomment-43488854)      |
| 2014-11 | [GitHub][]                   | Bug          | [Glitches for filenames that contain only spaces](https://github.com/isaacs/github/issues/286)                                                             |
| 2014-11 | [GitHub][]                   | Bug          | [500 on raw and 414 on blob show of long file name with 1024 characters](https://github.com/isaacs/github/issues/290)                                      |
| 2014-11 | [GitHub][]                   | Feature      | [Highlight bytes / words in diffs on adjacent multi-line modifications](https://github.com/isaacs/github/issues/235)                                       |
| 2014-11 | [GitHub][]                   | Duplicate    | [Allow following of groups similar to following users](https://github.com/isaacs/github/issues/218#issuecomment-47030350)                                  |
{: .patches-table .data-table}

### Open source

| Date    | Project                      | Size | Description                                                                                                                                                               |
|---------|------------------------------|------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2019-04 | [gnuplot][]                  |      | [Why does plotting with point labels make plot generation extremely slow?](https://groups.google.com/forum/#!topic/comp.graphics.apps.gnuplot/qpL8aJIi9ZE)                |
| 2019-04 | [GDB dashboard][]            |      | [Limit the size of shown arguments in the Stack display](https://github.com/cyrus-and/gdb-dashboard/issues/142)                                                           |
| 2018-03 | [QEMU][]                     | 2    | [Test record and replay feature](https://lists.nongnu.org/archive/html/qemu-devel/2018-02/msg01681.html). Also [here](https://bugs.launchpad.net/qemu/+bug/1762179)       |
| 2018-02 | [pandoc][]                   |      | [Add option to produce asciidoc output without explicit heading ids](https://github.com/jgm/pandoc/issues/4363)                                                           |
| 2017-10 | [AOSP][]                     |      | [GLES3 content gles3jni from ndk examples fails with "java.lang.RuntimeException: createContext failed: EGL_BAD_CONFIG"](https://issuetracker.google.com/issues/68496715) |
| 2017-09 | [rr][]                       |      | [How to automatically start replay and go directly to main instead of `_start`?](https://github.com/mozilla/rr/issues/2098)                                               |
| 2017-09 | [rr][]                       |      | [Reverse step over time(NULL) enters rr/src/preload/syscall_hook.S and leads to "Cannot find bounds of current function"](https://github.com/mozilla/rr/issues/2088)      |
| 2017-08 | [xsel][]                     |      | [Why maximum 4000 characters output with xsel -b ?](https://github.com/kfish/xsel/issues/13)                                                                              |
| 2017-06 | [Buildroot][]                |      | [Don't print mutiline struct function arguments on stack when set pretty print on](https://github.com/cyrus-and/gdb-dashboard/issues/65)                                  |
| 2017-04 | [GDB dashboard][]            |      | [Add style option to print stack arguments on a single line](https://github.com/cyrus-and/gdb-dashboard/issues/60)                                                        |
| 2017-05 | [Buildroot][]                |      | [Build fails with "unexpected EOF while looking for matching "'" if PATH contains a newline](https://bugs.busybox.net/show_bug.cgi?id=9886)                               |
| 2017-04 | [GDB dashboard][]            |      | [Add style option to print stack arguments on a single line](https://github.com/cyrus-and/gdb-dashboard/issues/60)                                                        |
| 2017-03 | [clBLAS][]                   |      | [`.s[0]` + CL_DEVICE_TYPE_ALL](https://github.com/clMathLibraries/clBLAS/pull/313)                                                                                        |
| 2017-01 | [Game Icons][]               |      | [Use multiple separate paths, allow customizing the color of each component, and give a default color](https://github.com/game-icons/icons/issues/301)                    |
| 2017-01 | [Game Icons][]               |      | [delapouite/originals/svg/brick-wall.svg has some whitespace on top](https://github.com/game-icons/icons/issues/302)                                                      |
| 2017-01 | [OpenAI Gym][]               |      | [examples/agents/keyboard_agent.py fails with "AttributeError: 'TimeLimit' object has no attribute 'viewer'"](https://github.com/openai/gym/issues/483)                   |
| 2016-12 | [SDL][]                      |      | [Add C variable printf debug snippets](https://hg.libsdl.org/SDL/rev/a458fc3377dc)                                                                                        |
| 2015-03 | [Tig][]                      |      | [Accepted feature.](https://github.com/jonas/tig/issues/273)                                                                                                              |
| 2014-11 | [GitLab][]                   |      | [Duplicate](https://github.com/gitlabhq/gitlabhq/issues/8293#issuecomment-62858344)                                                                                       |
| 2014-11 | [GitLab][]                   |      | [Bug.](https://gitlab.com/gitlab-com/www-gitlab-com/issues/180)                                                                                                           |
| 2014-11 | [GitLab][]                   |      | [Support.](https://github.com/gitlabhq/gitlabhq/issues/8384)                                                                                                              |
| 2014-11 | [Bootstrap Hover Dropdown][] |      | [Bug confirmed.](https://github.com/CWSpear/bootstrap-hover-dropdown/issues/92)                                                                                           |
| 2014-11 | [GitLab][]                   |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/issues/8267)                                                                                                        |
| 2014-11 | [GitLab][]                   |      | [Triaging.](https://github.com/gitlabhq/gitlabhq/issues/8357)                                                                                                             |
| 2014-11 | [GitLab][]                   |      | [Problem with the display icons in the left block](https://github.com/gitlabhq/gitlabhq/issues/8302)                                                                      |
| 2014-11 | [Sass][]                     |      | [Bug confirmed.](https://github.com/sass/sass/issues/1493)                                                                                                                |
| 2014-10 | [GitLab][]                   |      | [Point duplicate.](https://github.com/gitlabhq/gitlabhq/issues/8206)                                                                                                      |
| 2014-10 | [GitLab][]                   |      | [Bug confirmed.](https://gitlab.com/gitlab-com/www-gitlab-com/issues/170)                                                                                                 |
| 2014-10 | [GitLab][]                   |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/issues/8090)                                                                                                        |
| 2014-10 | [Semaphore CI][]             |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/pull/8081)                                                                                                          |
| 2014-10 | [libgit2][]                  |      | [Bug confirmed.](https://github.com/libgit2/libgit2/issues/2562)                                                                                                          |
| 2014-10 | [GitLab][]                   |      | [Support.](https://github.com/gitlabhq/gitlabhq/issues/8038)                                                                                                              |
| 2014-10 | [GitLab][]                   |      | [Point duplicate.](https://feedback.gitlab.com/forums/176466-general/suggestions/3922228-opt-into-and-out-of-notifications-for-specific-iss)                              |
| 2014-09 | [vader.vim][]                |      | [Accepted feature.](https://github.com/junegunn/vader.vim/issues/15)                                                                                                      |
| 2014-09 | [GitLab][]                   |      | [Point already fixed.](https://feedback.gitlab.com/forums/176466-general/suggestions/5004385-wrap-lines-option-in-the-merge-request)                                      |
| 2014-09 | [vader.vim][]                |      | [Accepted feature.](https://github.com/junegunn/vader.vim/issues/14)                                                                                                      |
| 2014-09 | [GitLab][]                   |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/pull/7242)                                                                                                          |
| 2014-09 | [GitLab][]                   |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/issues/6351)                                                                                                        |
| 2014-09 | [GitLab][]                   |      | [Point duplicate.](https://feedback.gitlab.com/forums/176466-general/suggestions/4077791-login-gitlab-as-another-user-impersonate-functio)                                |
| 2014-09 | [GitLab][]                   |      | [Point already fixed.](https://feedback.gitlab.com/forums/176466-general/suggestions/5567051-delete-branch-after-accepting-or-closing-a-merge-r)                          |
| 2014-08 | [Markdown lint][]            |      | [Accepted feature.](https://github.com/mivok/markdownlint/issues/47)                                                                                                      |
| 2014-08 | [Softcover][]                |      | [Accepted feature.](https://groups.google.com/forum/?hl=en#!topic/softcover-publishing/zFrDngqlYbY)                                                                       |
| 2014-08 | [Markdown lint][]            |      | [Accepted feature.](https://github.com/mivok/markdownlint/issues/49)                                                                                                      |
| 2014-07 | [GitLab][]                   |      | [Bug confirmed.](https://github.com/gitlabhq/gitlabhq/pull/7257)                                                                                                          |
| 2014-07 | [GitLab][]                   |      | [Accepted feature.](https://feedback.gitlab.com/forums/176466-general/suggestions/5863024-ability-to-dismiss-a-broadcast-messages)                                        |
| 2014-07 | [GitLab][]                   |      | [Accepted feature.](https://feedback.gitlab.com/forums/176466-general/suggestions/5590496-resolve-any-merge-request-conflict-from-the-web-in)                             |
| 2014-06 | [isaacs/github][]            |      | [Point duplicate.](https://github.com/isaacs/github/issues/218)                                                                                                           |
| 2014-06 | [GitLab][]                   |      | [Accepted feature.](https://feedback.gitlab.com/forums/176466-general/suggestions/5578188-use-something-more-meaningful-than-www-to-differen)                             |
| 2014-06 | [GitLab][]                   |      | [Point duplicate.](https://github.com/gitlabhq/gitlabhq/issues/6655#issuecomment-47034956)                                                                                |
| 2014-06 | [Markdown Test Suite][]      |      | [Bug confirmed.](https://github.com/karlcow/markdown-testsuite/issues/37)                                                                                                 |
| 2014-06 | [Vim Markdown][]             |      | [Close issue.](https://github.com/plasticboy/vim-markdown/issues/74#issuecomment-46292801)                                                                                |
| 2014-06 | [Vim Markdown][]             |      | [Review patch.](https://github.com/plasticboy/vim-markdown/pull/92)                                                                                                       |
| 2014-06 | [Vim Markdown][]             |      | [Review and patch patch.](https://github.com/plasticboy/vim-markdown/pull/80)                                                                                             |
| 2014-05 | [Softcover][]                |      | [Accepted feature.](https://github.com/softcover/softcover/pull/94)                                                                                                       |
| 2014-04 | [Markdown Test Suite][]      |      | [Close issue with better issues.](https://github.com/karlcow/markdown-testsuite/issues/3)                                                                                 |
| 2014-03 | [Tig][]                      |      | [Accepted feature.](https://github.com/jonas/tig/issues/275)                                                                                                              |
| 2014-03 | [GitLab][]                   |      | [Accepted feature.](https://feedback.gitlab.com/forums/176466-general/suggestions/5518180-smarter-merge-request-target-repo-and-branch-form-)                             |
| 2014-03 | [Softcover][]                |      | [Accepted feature.](https://github.com/softcover/polytexnic/issues/100#issuecomment-37228903)                                                                             |
| 2014-03 | [GitLab][]                   |      | [Add useful information.](https://feedback.gitlab.com/forums/176466-general/suggestions/5603753-gitlab-markdown-should-display-username-s-correct)                        |
| 2014-03 | [GitLab][]                   |      | [Point duplicate.](https://feedback.gitlab.com/forums/176466-general/suggestions/5628857-administratively-create-issues-on-behalf-of-other)                               |
| 2014-03 | [GitLab][]                   |      | [Point duplicate.](https://feedback.gitlab.com/forums/176466-general/suggestions/3957367-allowing-the-build-pages-to-be-viewed-publicly)                                  |
| 2014-03 | [GitLab][]                   |      | [Accepted feature.](https://feedback.gitlab.com/forums/176466-general/suggestions/5607934-view-diff-on-submit-merge-request-form)                                         |
| 2014-02 | [GitLab][]                   |      | [Point duplicate.](https://feedback.gitlab.com/forums/176466-general/suggestions/4255282-task-lists-like-github-done-or-some-other-implemen)                              |
| 2014-02 | [GitLab][]                   |      | [Accepted feature.](https://github.com/gitlabhq/gitlabhq/pull/6389)                                                                                                       |
| 2014-02 | [ShareLaTeX][]               |      | [Feature generated considerable interest.](https://github.com/sharelatex/sharelatex/issues/51)                                                                            |
| 2014-02 | [GitLab][]                   |      | [Point already fixed.](https://feedback.gitlab.com/forums/176466-general/suggestions/3941049-allow-public-read-only-wikis)                                                |
| 2014-02 | [GitLab][]                   |      | [Link feature request to patch.](https://feedback.gitlab.com/forums/176466-general/suggestions/4000912-add-a-diff-view-when-editing-a-file-via-the-web-in)                |
| 2013-10 | [Yakuake][]                  |      | [Bug confirmed.](https://bugs.kde.org/show_bug.cgi?id=319172#c2)                                                                                                          |
| 2013-10 | [Okular][]                   |      | [Bug confirmed.](https://bugs.kde.org/show_bug.cgi?id=327641)                                                                                                             |
| 2013-06 | [Krusader][]                 |      | [Bug confirmed.](https://bugs.launchpad.net/ubuntu/+source/krusader/+bug/1197679)                                                                                         |
| 2013-05 | [NumPy][]                    |      | [Bug confirmed + inner cause.](https://github.com/matplotlib/matplotlib/pull/1967)                                                                                        |
| 2012-05 | [Krusader][]                 |      | [Accepted feature.](https://bugs.kde.org/show_bug.cgi?id=300068)                                                                                                          |
| 2012-05 | [Krusader][]                 |      | [Bug confirmed.](https://bugs.launchpad.net/ubuntu/+source/krusader/+bug/999695)                                                                                          |
| 2012-05 | [AutoKey][]                  |      | [Bug confirmed.](https://code.google.com/p/autokey/issues/detail?id=197)                                                                                                  |
{: #bugs-table .data-table}

### Not verified

The following contributions where not immediately verified by others, but they were not reverted either and I think they are good.

| Date    | Project          | Type         | Description                                                                         |
|---------|------------------|--------------|-------------------------------------------------------------------------------------|
| 2014-12 | [Vim Markdown][] | Review patch | [Add tilde-fenced code blocks](https://github.com/plasticboy/vim-markdown/pull/158) |
{: .patches-table .data-table}

## Security

| Date    | Project                      | Size | Description                                                                                  |
|---------|------------------------------|------|----------------------------------------------------------------------------------------------|
| 2016-05 | [All GitHub Commit Emails][] | 1    | Password disclosure `grep password` on email data. Gmail password worked and user confirmed. |
{: .patches-table .data-table}

{% include links.md %}

# 3rd party Debian packages used in daichan

```text

====================
build-essential
====================

This package contains an informational list of Build-Essential Debian
packages.

Copyright © 2003-2005 Scott James Remnant <scott@netsplit.com>
Copyright © 2003 Colin Walters <walters@debian.org>
Copyright © 1999-2002 Antti-Juhani Kaijanaho <ajk@debian.org>
Copyright © 2006-2016 Matthas Klose <doko@debian.org>


License:

The files in this package are free software; you can redistribute them
and/or modify them under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2, or (at
your option) any later version.

The files in this package are distributed in the hope that they will
be useful, but WITHOUT ANY WARRANTY; without even the implied warranty
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

On Debian GNU/Linux systems, the complete text of the GNU General Public
License can be found in `/usr/share/common-licenses/GPL'.


====================
libbz2-dev
====================

--------------------------------------------------------------------------

This program, "bzip2", the associated library "libbzip2", and all
documentation, are copyright (C) 1996-2010 Julian R Seward.  All
rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

2. The origin of this software must not be misrepresented; you must
   not claim that you wrote the original software.  If you use this
   software in a product, an acknowledgment in the product
   documentation would be appreciated but is not required.

3. Altered source versions must be plainly marked as such, and must
   not be misrepresented as being the original software.

4. The name of the author may not be used to endorse or promote
   products derived from this software without specific prior written
   permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS
OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Julian Seward, jseward@acm.org
bzip2/libbzip2 version 1.1.0 of 6 September 2010

--------------------------------------------------------------------------


====================
libncursesw5-dev
====================

Copyright 2018-2022,2023 Thomas E. Dickey
Copyright 1998-2017,2018 Free Software Foundation, Inc.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, distribute with modifications, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE ABOVE COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Except as contained in this notice, the name(s) of the above copyright
holders shall not be used in advertising or otherwise to promote the
sale, use or other dealings in this Software without prior written
authorization.

-- vile:txtmode fc=72
-- $Id: COPYING,v 1.12 2023/01/07 17:55:53 tom Exp $


====================
libssl-dev
====================

This package was debianized by Christoph Martin martin@uni-mainz.de on
Fri, 22 Nov 1996 21:29:51 +0100.

Copyright (c) 1998-2004 The OpenSSL Project
Copyright (c) 1995-1998 Eric A. Young, Tim J. Hudson

The upstream sources were obtained from https://www.openssl.org/


  LICENSE ISSUES
  ==============

  The OpenSSL toolkit stays under a dual license, i.e. both the conditions of
  the OpenSSL License and the original SSLeay license apply to the toolkit.
  See below for the actual license texts. Actually both licenses are BSD-style
  Open Source licenses. In case of any license issues related to OpenSSL
  please contact openssl-core@openssl.org.

  OpenSSL License
  ---------------

/* ====================================================================
 * Copyright (c) 1998-2004 The OpenSSL Project.  All rights reserved.
 *
 * Redistribution and use in source and binary forms, with or without
 * modification, are permitted provided that the following conditions
 * are met:
 *
 * 1. Redistributions of source code must retain the above copyright
 *    notice, this list of conditions and the following disclaimer.
 *
 * 2. Redistributions in binary form must reproduce the above copyright
 *    notice, this list of conditions and the following disclaimer in
 *    the documentation and/or other materials provided with the
 *    distribution.
 *
 * 3. All advertising materials mentioning features or use of this
 *    software must display the following acknowledgment:
 *    "This product includes software developed by the OpenSSL Project
 *    for use in the OpenSSL Toolkit. (http://www.openssl.org/)"
 *
 * 4. The names "OpenSSL Toolkit" and "OpenSSL Project" must not be used to
 *    endorse or promote products derived from this software without
 *    prior written permission. For written permission, please contact
 *    openssl-core@openssl.org.
 *
 * 5. Products derived from this software may not be called "OpenSSL"
 *    nor may "OpenSSL" appear in their names without prior written
 *    permission of the OpenSSL Project.
 *
 * 6. Redistributions of any form whatsoever must retain the following
 *    acknowledgment:
 *    "This product includes software developed by the OpenSSL Project
 *    for use in the OpenSSL Toolkit (http://www.openssl.org/)"
 *
 * THIS SOFTWARE IS PROVIDED BY THE OpenSSL PROJECT ``AS IS'' AND ANY
 * EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
 * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
 * PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE OpenSSL PROJECT OR
 * ITS CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
 * SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
 * NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
 * LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
 * HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
 * STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
 * ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED
 * OF THE POSSIBILITY OF SUCH DAMAGE.
 * ====================================================================
 *
 * This product includes cryptographic software written by Eric Young
 * (eay@cryptsoft.com).  This product includes software written by Tim
 * Hudson (tjh@cryptsoft.com).
 *
 */

 Original SSLeay License
 -----------------------

/* Copyright (C) 1995-1998 Eric Young (eay@cryptsoft.com)
 * All rights reserved.
 *
 * This package is an SSL implementation written
 * by Eric Young (eay@cryptsoft.com).
 * The implementation was written so as to conform with Netscapes SSL.
 *
 * This library is free for commercial and non-commercial use as long as
 * the following conditions are aheared to.  The following conditions
 * apply to all code found in this distribution, be it the RC4, RSA,
 * lhash, DES, etc., code; not just the SSL code.  The SSL documentation
 * included with this distribution is covered by the same copyright terms
 * except that the holder is Tim Hudson (tjh@cryptsoft.com).
 *
 * Copyright remains Eric Young's, and as such any Copyright notices in
 * the code are not to be removed.
 * If this package is used in a product, Eric Young should be given attribution
 * as the author of the parts of the library used.
 * This can be in the form of a textual message at program startup or
 * in documentation (online or textual) provided with the package.
 *
 * Redistribution and use in source and binary forms, with or without
 * modification, are permitted provided that the following conditions
 * are met:
 * 1. Redistributions of source code must retain the copyright
 *    notice, this list of conditions and the following disclaimer.
 * 2. Redistributions in binary form must reproduce the above copyright
 *    notice, this list of conditions and the following disclaimer in the
 *    documentation and/or other materials provided with the distribution.
 * 3. All advertising materials mentioning features or use of this software
 *    must display the following acknowledgement:
 *    "This product includes cryptographic software written by
 *     Eric Young (eay@cryptsoft.com)"
 *    The word 'cryptographic' can be left out if the rouines from the library
 *    being used are not cryptographic related :-).
 * 4. If you include any Windows specific code (or a derivative thereof) from
 *    the apps directory (application code) you must include an acknowledgement:
 *    "This product includes software written by Tim Hudson (tjh@cryptsoft.com)"
 *
 * THIS SOFTWARE IS PROVIDED BY ERIC YOUNG ``AS IS'' AND
 * ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
 * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
 * ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
 * FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
 * DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
 * OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
 * HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
 * LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
 * OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
 * SUCH DAMAGE.
 *
 * The licence and distribution terms for any publically available version or
 * derivative of this code cannot be changed.  i.e. this code cannot simply be
 * copied and put under another distribution licence
 * [including the GNU Public Licence.]
 */


====================
zlib1g-dev
====================

Copyright notice:

 (C) 1995-2022 Jean-loup Gailly and Mark Adler

  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.

  Jean-loup Gailly        Mark Adler
  jloup@gzip.org          madler@alumni.caltech.edu


====================
Python-3.8.13
====================

https://docs.python.org/3/license.html


====================
vim
====================

VIM LICENSE

I)  There are no restrictions on distributing unmodified copies of Vim except
    that they must include this license text.  You can also distribute
    unmodified parts of Vim, likewise unrestricted except that they must
    include this license text.  You are also allowed to include executables
    that you made from the unmodified Vim sources, plus your own usage
    examples and Vim scripts.

II) It is allowed to distribute a modified (or extended) version of Vim,
    including executables and/or source code, when the following four
    conditions are met:
    1) This license text must be included unmodified.
    2) The modified Vim must be distributed in one of the following five ways:
       a) If you make changes to Vim yourself, you must clearly describe in
          the distribution how to contact you.  When the maintainer asks you
          (in any way) for a copy of the modified Vim you distributed, you
          must make your changes, including source code, available to the
          maintainer without fee.  The maintainer reserves the right to
          include your changes in the official version of Vim.  What the
          maintainer will do with your changes and under what license they
          will be distributed is negotiable.  If there has been no negotiation
          then this license, or a later version, also applies to your changes.
          The current maintainer is Bram Moolenaar <Bram@vim.org>.  If this
          changes it will be announced in appropriate places (most likely
          vim.sf.net, www.vim.org and/or comp.editors). When it is completely
          impossible to contact the maintainer, the obligation to send him
          your changes ceases.  Once the maintainer has confirmed that he has
          received your changes they will not have to be sent again.
       b) If you have received a modified Vim that was distributed as
          mentioned under a) you are allowed to further distribute it
          unmodified, as mentioned at I).  If you make additional changes the
          text under a) applies to those changes.
       c) Provide all the changes, including source code, with every copy of
          the modified Vim you distribute.  This may be done in the form of a
          context diff.  You can choose what license to use for new code you
          add.  The changes and their license must not restrict others from
          making their own changes to the official version of Vim.
       d) When you have a modified Vim which includes changes as mentioned
          under c), you can distribute it without the source code for the
          changes if the following three conditions are met:
          - The license that applies to the changes permits you to distribute
            the changes to the Vim maintainer without fee or restriction, and
            permits the Vim maintainer to include the changes in the official
            version of Vim without fee or restriction.
          - You keep the changes for at least three years after last
            distributing the corresponding modified Vim.  When the maintainer
            or someone who you distributed the modified Vim to asks you (in
            any way) for the changes within this period, you must make them
            available to him.
          - You clearly describe in the distribution how to contact you.  This
            contact information must remain valid for at least three years
            after last distributing the corresponding modified Vim, or as long
            as possible.
       e) When the GNU General Public License (GPL) applies to the changes,
          you can distribute the modified Vim under the GNU GPL version 2 or
          any later version.
    3) A message must be added, at least in the output of the ":version"
       command and in the intro screen, such that the user of the modified Vim
       is able to see that it was modified.  When distributing as mentioned
       under 2)e) adding the message is only required for as far as this does
       not conflict with the license used for the changes.
    4) The contact information as required under 2)a) and 2)d) must not be
       removed or changed, except that the person himself can make
       corrections.

III) If you distribute a modified version of Vim, you are encouraged to use
     the Vim license for your changes and make them available to the
     maintainer, including the source code.  The preferred way to do this is
     by e-mail or by uploading the files to a server and e-mailing the URL.
     If the number of changes is small (e.g., a modified Makefile) e-mailing a
     context diff will do.  The e-mail address to be used is
     <maintainer@vim.org>

IV)  It is not allowed to remove this license from the distribution of the Vim
     sources, parts of it or from a modified version.  You may use this
     license for previous Vim releases instead of the license that they came
     with, at your option.


====================
python3-pyaudio
====================

Copyright (c) 2006-2014 Hubert Pham

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


====================
portaudio19-dev
====================

This package was debianized by Mikael Magnusson
<mikma@users.sourceforge.net> on Mon, 12 Jul 2004 13:23:58 +0000.

It was downloaded from:
https://www.portaudio.com/repos/portaudio/branches/v19-devel

Upstream Authors:
Ross Bencina <rbencina@iprimus.com.au>
Phil Burk <philburk@softsynth.com>

Copyright:

PortAudio Portable Real-Time Audio Library
Copyright (c) 1999-2009 Ross Bencina
Copyright (c) 1999-2008 Phil Burk
Copyright (c) 1999-2000 Robert Marsanyi
Copyright (c) 1999-2007 Andrew Baldwin
Copyright (c) 2002 Joshua Haberman <joshua@haberman.com>
Copyright (c) 2003 Fred Gleason
Copyright (c) 2004 Stefan Westerfeld <stefan@space.twc.de>
Copyright (c) 2004-2009 Arve Knudsen <arve.knudsen@gmail.com>
Copyright (c) 2005-2006 Ludwig Schwardt
Copyright (c) 2006-2007 David Viens
Copyright (c) 2008 Kevin Kofler <kevin.kofler@chello.at>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files
(the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge,
publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR
ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


The text above constitutes the entire PortAudio license; however,
the PortAudio community also makes the following non-binding requests:

Any person wishing to distribute modifications to the Software is
requested to send the modifications to the original developer so that
they can be incorporated into the canonical version. It is also
requested that these non-binding requests be included along with the
license above.


====================
libatlas-base-dev
====================

Format: https://www.debian.org/doc/packaging-manuals/copyright-format/1.0/
Upstream-Name: ATLAS
Upstream-Contact: R. Clint Whaley <rcwhaley@lsu.edu>
Source: http://math-atlas.sourceforge.net/

Files: *
Copyright: 1997-2016 R. Clint Whaley
           1999-2000, 2004 Antoine P. Petitet
           2000-2001 Peter Soendergaard
           2009, 2012 Siju Samuel
           2001 Julian Ruhe
           2010 IBM Corporation
           1998 Jeff Horner
           2011 Md. Rakib Hasan
           2010-2011 Vesperix Corporation
           2009 Chad Zalkin
           2011 Md. Majedul Haque Sujon
           1999 The Australian National University
License: BSD-3-clause-ATLAS
 Redistribution  and  use in  source and binary forms, with or without
 modification, are  permitted provided  that the following  conditions
 are met:
 .
 1. Redistributions  of  source  code  must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce  the above copyright
    notice,  this list of conditions, and the  following disclaimer in
    the documentation and/or other materials provided with the distri-
    bution.
 3. The name of the University,  the ATLAS group,  or the names of its
    contributors  may not be used to endorse or promote products deri-
    ved from this software without specific written permission.
 .
 THIS  SOFTWARE  IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
 ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES,  INCLUDING,  BUT NOT
 LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
 A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE UNIVERSITY
 OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,  INDIRECT, INCIDENTAL, SPE-
 CIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
 TO,  PROCUREMENT  OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA,
 OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEO-
 RY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT  (IN-
 CLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
 THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Files: interfaces/blas/F77/src/lsame.f
       src/blas/f77reference/*
Copyright: 1992-2017 The University of Tennessee and The University of Tennessee Research Foundation
           2000-2017 The University of California Berkeley
           2006-2017 The University of Colorado Denverf
License: BSD-3-clause

Files: bin/extract.c
Copyright: 1994, 2015, R. Clint Whaley (rwhaley@cs.utk.edu)
License: GPL-2-modified
 This program is distributed under the terms of the Gnu
 General Public License (GPL), with the following two exceptions:
 (1) Clause (9), dealing with updating the GPL automatically, is
     specifically disallowed by the author.  The author will
     determine if a newer GPL version is still appropriate.
 (2) The basefiles extract accepts as input, and the extracted
     files it produces as output, are specifically designated
     as outside the scope if this license (i.e. they are *not*
     required by this license to be GPL).
 The full, unaltered, text of the GPL is included at the end of
 the program source listing.
 .
 On Debian systems, the complete text of the GNU General Public
 License, version 2, can be found in the file
 `/usr/share/common-licenses/GPL-2'.

Files: tune/blas/gemm/CASES/ATL_smm_3dnow_90.c
Copyright: none
License: public-domain
 The authors and University of Kentucky make this software freely
 available as a PUBLIC DOMAIN release.  None of the authors nor
 University of Kentucky can be held responsible for any problems
 deriving from use of this software.
 .
 The primary author is:
 .
         Tim Mattox
         Department of Electrical and Computer Engineering
         University of Kentucky
         Lexington, KY  40506-0046
         email: tmattox@engr.uky.edu
         URL: http://aggregate.org/

Files: debian/*
Copyright: 1999-2007 Camm Maguire <camm@enhanced.com>
           2008-2013 Sylvestre Ledru <sylvestre@debian.org>
           2013-2017 Sébastien Villemot <sebastien@debian.org>
License: BSD-3-clause

License: BSD-3-clause
 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are
 met:
 .
 - Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
 .
 - Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer listed
   in this license in the documentation and/or other materials
   provided with the distribution.
 .
 - Neither the name of the copyright holders nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.
 .
 The copyright holders provide no reassurances that the source code
 provided does not infringe any patent, copyright, or any other
 intellectual property rights of third parties.  The copyright holders
 disclaim any liability to any recipient for claims brought against
 recipient by any third party for infringement of that parties
 intellectual property rights.
 .
 THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
 "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
 LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
 A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
 OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
 SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
 LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
 DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
 THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
 (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
 OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


====================
python3-numpy
====================

This package was debianized by Marco Presi (Zufus) <zufus@debian.org> on
Tue, 14 Feb 2006 00:40:53 +0100.

It was downloaded from http://www.numpy.org/

Copyright:

    Copyright (c) 2005-2019, NumPy Developers <numpy-dev@numpy.org>

License:

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are
    met:

        * Redistributions of source code must retain the above copyright
           notice, this list of conditions and the following disclaimer.

        * Redistributions in binary form must reproduce the above
           copyright notice, this list of conditions and the following
           disclaimer in the documentation and/or other materials provided
           with the distribution.

        * Neither the name of the NumPy Developers nor the names of any
           contributors may be used to endorse or promote products derived
           from this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
    OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
    SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
    LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
    DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
    THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The Debian packaging is Copyright (C) 2010-2019, Sandro Tosi <morph@debian.org>
and is licensed under the same terms as upstream code.


doc/scipy-sphinx-theme/
Copyright (c) 2011  Kevin Dunn, Surya K, Pauli Virtanen, the Sphinx team
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above
      copyright notice, this list of conditions and the following
      disclaimer in the documentation and/or other materials provided
      with the distribution.
    * Neither the name of the author nor the names of other
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


doc/scipy-sphinx-theme/_theme/scipy/static/js/copybutton.js
    Copyright 2014 Python Software Foundation
License: PSF
 PYTHON SOFTWARE FOUNDATION LICENSE VERSION 2
 --------------------------------------------
 .
 1. This LICENSE AGREEMENT is between the Python Software Foundation
 ("PSF"), and the Individual or Organization ("Licensee") accessing and
 otherwise using this software ("Python") in source or binary form and
 its associated documentation.
 .
 2. Subject to the terms and conditions of this License Agreement, PSF
 hereby grants Licensee a nonexclusive, royalty-free, world-wide
 license to reproduce, analyze, test, perform and/or display publicly,
 prepare derivative works, distribute, and otherwise use Python
 alone or in any derivative version, provided, however, that PSF's
 License Agreement and PSF's notice of copyright, i.e., "Copyright (c)
 2001, 2002, 2003, 2004, 2005, 2006 Python Software Foundation; All Rights
 Reserved" are retained in Python alone or in any derivative version
 prepared by Licensee.
 .
 3. In the event Licensee prepares a derivative work that is based on
 or incorporates Python or any part thereof, and wants to make
 the derivative work available to others as provided herein, then
 Licensee hereby agrees to include in any such work a brief summary of
 the changes made to Python.
 .
 4. PSF is making Python available to Licensee on an "AS IS"
 basis.  PSF MAKES NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR
 IMPLIED.  BY WAY OF EXAMPLE, BUT NOT LIMITATION, PSF MAKES NO AND
 DISCLAIMS ANY REPRESENTATION OR WARRANTY OF MERCHANTABILITY OR FITNESS
 FOR ANY PARTICULAR PURPOSE OR THAT THE USE OF PYTHON WILL NOT
 INFRINGE ANY THIRD PARTY RIGHTS.
 .
 5. PSF SHALL NOT BE LIABLE TO LICENSEE OR ANY OTHER USERS OF PYTHON
 FOR ANY INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES OR LOSS AS
 A RESULT OF MODIFYING, DISTRIBUTING, OR OTHERWISE USING PYTHON,
 OR ANY DERIVATIVE THEREOF, EVEN IF ADVISED OF THE POSSIBILITY THEREOF.
 .
 6. This License Agreement will automatically terminate upon a material
 breach of its terms and conditions.
 .
 7. Nothing in this License Agreement shall be deemed to create any
 relationship of agency, partnership, or joint venture between PSF and
 Licensee.  This License Agreement does not grant permission to use PSF
 trademarks or trade name in a trademark sense to endorse or promote
 products or services of Licensee, or any third party.
 .
 8. By copying, installing or otherwise using Python, Licensee
 agrees to be bound by the terms and conditions of this License
 Agreement.


numpy/core/src/umath/{reduction.c, ufunc_type_resolution.c
    Written by Mark Wiebe (mwwiebe@gmail.com)
    Copyright (c) 2011 by Enthought, Inc.


numpy/core/src/umath/ufunc_object.c
    Travis E. Oliphant  2005, 2006 oliphant@ee.byu.edu (oliphant.travis@ieee.org)
    Brigham Young University

    based on the

    Original Implementation:
    Copyright (c) 1995, 1996, 1997 Jim Hugunin, hugunin@mit.edu

    with inspiration and code from
    Numarray
    Space Science Telescope Institute
    J. Todd Miller
    Perry Greenfield
    Rick White


numpy/core/arrayprint.py
    Written by Konrad Hinsen <hinsenk@ere.umontreal.ca>
    last revision: 1996-3-13
    modified by Jim Hugunin 1997-3-3 for repr's and str's (and other details)
    and by Perry Greenfield 2000-4-1 for numarray
    and by Travis Oliphant  2005-8-22 for numpy


numpy/oldnumeric/ma.py
    Copyright 1999, 2000, 2001 Regents of the University of California.
    Released for unlimited redistribution.
    Adapted for numpy_core 2005 by Travis Oliphant and
    (mainly) Paul Dubois.


numpy/core/src/multiarray/{arrayobject.c, usertypes.c}
    Based on Original Numeric implementation
    Copyright (c) 1995, 1996, 1997 Jim Hugunin, hugunin@mit.edu

    with contributions from many Numeric Python developers 1995-2004

    Heavily modified in 2005 with inspiration from Numarray

    by

    Travis Oliphant,  oliphant@ee.byu.edu
    Brigham Young Univeristy

    maintainer email:  oliphant.travis@ieee.org

    Numarray design (which provided guidance) by
    Space Science Telescope Institute
    (J. Todd Miller, Perry Greenfield, Rick White)


numpy/core/src/multiarray/multiarraymodule.c
    Original file
    Copyright (c) 1995, 1996, 1997 Jim Hugunin, hugunin@mit.edu

    Modified for numpy in 2005

    Travis E. Oliphant
    oliphant@ee.byu.edu
    Brigham Young University


numpy/core/src/npymath/npy_math.c.src
    Some of the code is taken from msun library in FreeBSD, with the following
    notice:

    ====================================================
    Copyright (C) 1993 by Sun Microsystems, Inc. All rights reserved.

    Developed at SunPro, a Sun Microsystems, Inc. business.
    Permission to use, copy, modify, and distribute this
    software is freely granted, provided that this notice
    is preserved.
    ====================================================


numpy/core/src/npymath/npy_math_complex.c.src
    Most of the code is taken from the msun library in FreeBSD (HEAD @ 4th
    October 2013), under the following license:

    Copyright (c) 2007, 2011 David Schultz <das@FreeBSD.ORG>
    Copyright (c) 2012 Stephen Montgomery-Smith <stephen@FreeBSD.ORG>
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:
    1. Redistributions of source code must retain the above copyright
       notice, this list of conditions and the following disclaimer.
    2. Redistributions in binary form must reproduce the above copyright
       notice, this list of conditions and the following disclaimer in the
       documentation and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS'' AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
    OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
    LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
    OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
    SUCH DAMAGE.


numpy/core/src/npymath/npy_math_private.h
    ====================================================
    Copyright (C) 1993 by Sun Microsystems, Inc. All rights reserved.

    Developed at SunPro, a Sun Microsystems, Inc. business.
    Permission to use, copy, modify, and distribute this
    software is freely granted, provided that this notice
    is preserved.
    ====================================================


numpy/distutils/cpuinfo.py
    Copyright 2002 Pearu Peterson all rights reserved,
    Pearu Peterson <pearu@cens.ioc.ee>
    Permission to use, modify, and distribute this software is given under the
    terms of the NumPy (BSD style) license.  See LICENSE.txt that came with
    this distribution for specifics.

    NO WARRANTY IS EXPRESSED OR IMPLIED.  USE AT YOUR OWN RISK.
    Pearu Peterson


numpy/distutils/system_info.py
    Authors:
      Pearu Peterson <pearu@cens.ioc.ee>, February 2002
      David M. Cooke <cookedm@physics.mcmaster.ca>, April 2002

    Copyright 2002 Pearu Peterson all rights reserved,
    Pearu Peterson <pearu@cens.ioc.ee>
    Permission to use, modify, and distribute this software is given under the
    terms of the NumPy (BSD style) license.  See LICENSE.txt that came with
    this distribution for specifics.

    NO WARRANTY IS EXPRESSED OR IMPLIED.  USE AT YOUR OWN RISK.


numpy/random/mtrand/distributions.c
    Copyright 2005 Robert Kern (robert.kern@gmail.com)

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
    OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

    The implementations of rk_hypergeometric_hyp(), rk_hypergeometric_hrua(),
    and rk_triangular() were adapted from Ivan Frohne's rv.py which has this
    license:

               Copyright 1998 by Ivan Frohne; Wasilla, Alaska, U.S.A.
                               All Rights Reserved

    Permission to use, copy, modify and distribute this software and its
    documentation for any purpose, free of charge, is granted subject to the
    following conditions:
      The above copyright notice and this permission notice shall be included in
      all copies or substantial portions of the software.

      THE SOFTWARE AND DOCUMENTATION IS PROVIDED WITHOUT WARRANTY OF ANY KIND,
      EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO MERCHANTABILITY, FITNESS
      FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHOR
      OR COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM OR DAMAGES IN A CONTRACT
      ACTION, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
      SOFTWARE OR ITS DOCUMENTATION.


numpy/random/mtrand/randomkit.h
    Copyright (c) 2003-2005, Jean-Sebastien Roy (js@jeannot.org)

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
    OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


numpy/random/mtrand/initarray.c
    The following changes have been made to it in 2005 by Robert Kern:

      * init_by_array has been declared extern, has a void return, and uses the
        rk_state structure to hold its data.

     The original file has the following verbatim comments:

     ------------------------------------------------------------------
     The code in this module was based on a download from:
        http://www.math.keio.ac.jp/~matumoto/MT2002/emt19937ar.html

     It was modified in 2002 by Raymond Hettinger as follows:

      * the principal computational lines untouched except for tabbing.

      * renamed genrand_res53() to random_random() and wrapped
        in python calling/return code.

      * genrand_int32() and the helper functions, init_genrand()
        and init_by_array(), were declared static, wrapped in
        Python calling/return code.  also, their global data
        references were replaced with structure references.

      * unused functions from the original were deleted.
        new, original C python code was added to implement the
        Random() interface.

     The following are the verbatim comments from the original code:

     A C-program for MT19937, with initialization improved 2002/1/26.
     Coded by Takuji Nishimura and Makoto Matsumoto.

     Before using, initialize the state by using init_genrand(seed)
     or init_by_array(init_key, key_length).

     Copyright (C) 1997 - 2002, Makoto Matsumoto and Takuji Nishimura,
     All rights reserved.

     Redistribution and use in source and binary forms, with or without
     modification, are permitted provided that the following conditions
     are met:

       1. Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.

       2. Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.

       3. The names of its contributors may not be used to endorse or promote
      products derived from this software without specific prior written
      permission.

     THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
     "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
     LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
     A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR
     CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
     EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
     PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
     PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
     LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
     NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
     SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

     Any feedback is very welcome.
     http://www.math.keio.ac.jp/matumoto/emt.html
     email: matumoto@math.keio.ac.jp


numpy/random/mtrand/randomkit.c
    Copyright (c) 2003-2005, Jean-Sebastien Roy (js@jeannot.org)

    The rk_random and rk_seed functions algorithms and the original design of
    the Mersenne Twister RNG:

      Copyright (C) 1997 - 2002, Makoto Matsumoto and Takuji Nishimura,
      All rights reserved.

      Redistribution and use in source and binary forms, with or without
      modification, are permitted provided that the following conditions
      are met:

      1. Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.

      2. Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.

      3. The names of its contributors may not be used to endorse or promote
      products derived from this software without specific prior written
      permission.

      THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
      "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
      LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
      A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR
      CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
      EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
      PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
      PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
      LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
      NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
      SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

    Original algorithm for the implementation of rk_interval function from
    Richard J. Wagner's implementation of the Mersenne Twister RNG, optimised by
    Magnus Jonsson.

    Constants used in the rk_double implementation by Isaku Wada.

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
    OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


numpy/random/mtrand/{mtrand.pyx, distributions.h}
    Copyright 2005 Robert Kern (robert.kern@gmail.com)

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
    OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


numpy/random/mtrand/Python.pxi
    Author:    Robert Kern
    Copyright: 2004, Enthought, Inc.
    License:   BSD Style


numpy/f2py/*
    Copyright 1999-2011 Pearu Peterson all rights reserved,
    Pearu Peterson <pearu@ioc.ee>
    Permission to use, modify, and distribute this software is given under the
    terms of the NumPy License.

    NO WARRANTY IS EXPRESSED OR IMPLIED.  USE AT YOUR OWN RISK.


numpy/f2py/docs/{usersguide.}/default.css
    Author: David Goodger
    Contact: goodger@users.sourceforge.net
    copyright: This stylesheet has been placed in the public domain.


numpy/ma/*
    This package was initially written for numarray by Paul F. Dubois
    at Lawrence Livermore National Laboratory.
    In 2006, the package was completely rewritten by Pierre Gerard-Marchant
    (University of Georgia) to make the MaskedArray class a subclass of ndarray,
    and to improve support of structured arrays.

    Copyright 1999, 2000, 2001 Regents of the University of California.
    Released for unlimited redistribution.

    * Adapted for numpy_core 2005 by Travis Oliphant and (mainly) Paul Dubois.
    * Subclassing of the base ndarray 2006 by Pierre Gerard-Marchant
      (pgmdevlist_AT_gmail_DOT_com)
    * Improvements suggested by Reggie Dugard (reggie_AT_merfinllc_DOT_com)

    Author: Pierre Gerard-Marchant <pierregm_at_uga_dot_edu>


numpy/core/src/multiarray/{lowlevel_strided_loops.c.src, nditer_api.c,
                           nditer_constr.c, nditer_pywrap.c, nditer_templ.c.src}
    Copyright (c) 2010-2011 by Mark Wiebe (mwwiebe@gmail.com)
    The University of British Columbia


numpy/core/src/multiarray/{array_assign_array.c, array_assign.c,
                           array_assign_scalar.c, datetime_busday.c,
			   datetime_busdaycal.c, datetime.c, datetime_strings.c}
    Written by Mark Wiebe (mwwiebe@gmail.com)
    Copyright (c) 2011 by Enthought, Inc.


doc/cython/c_numpy.pxd, doc/pyrex/c_numpy.pxd
    Author: Travis Oliphant


doc/cython/c_python.pxd
    Author: Robert Kern
    Copyright: 2004, Enthought, Inc.
    License: BSD Style

From doc/sphinxext/LICENSE.txt:

-------------------------------------------------------------------------------
    The files
    - numpydoc.py
    - autosummary.py
    - autosummary_generate.py
    - docscrape.py
    - docscrape_sphinx.py
    - phantom_import.py
    have the following license:

Copyright (C) 2008 Stefan van der Walt <stefan@mentat.za.net>, Pauli Virtanen <pav@iki.fi>

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in
    the documentation and/or other materials provided with the
    distribution.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING
IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

-------------------------------------------------------------------------------
    The files
    - compiler_unparse.py
    - comment_eater.py
    - traitsdoc.py
    have the following license:

This software is OSI Certified Open Source Software.
OSI Certified is a certification mark of the Open Source Initiative.

Copyright (c) 2006, Enthought, Inc.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.
 * Neither the name of Enthought, Inc. nor the names of its contributors may
   be used to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


-------------------------------------------------------------------------------
    The files
    - only_directives.py
    - plot_directive.py
    originate from Matplotlib (http://matplotlib.sf.net/) which has
    the following license:

Copyright (c) 2002-2008 John D. Hunter; All Rights Reserved.

1. This LICENSE AGREEMENT is between John D. Hunter (“JDH”), and the Individual or Organization (“Licensee”) accessing and otherwise using matplotlib software in source or binary form and its associated documentation.

2. Subject to the terms and conditions of this License Agreement, JDH hereby grants Licensee a nonexclusive, royalty-free, world-wide license to reproduce, analyze, test, perform and/or display publicly, prepare derivative works, distribute, and otherwise use matplotlib 0.98.3 alone or in any derivative version, provided, however, that JDH’s License Agreement and JDH’s notice of copyright, i.e., “Copyright (c) 2002-2008 John D. Hunter; All Rights Reserved” are retained in matplotlib 0.98.3 alone or in any derivative version prepared by Licensee.

3. In the event Licensee prepares a derivative work that is based on or incorporates matplotlib 0.98.3 or any part thereof, and wants to make the derivative work available to others as provided herein, then Licensee hereby agrees to include in any such work a brief summary of the changes made to matplotlib 0.98.3.

4. JDH is making matplotlib 0.98.3 available to Licensee on an “AS IS” basis. JDH MAKES NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED. BY WAY OF EXAMPLE, BUT NOT LIMITATION, JDH MAKES NO AND DISCLAIMS ANY REPRESENTATION OR WARRANTY OF MERCHANTABILITY OR FITNESS FOR ANY PARTICULAR PURPOSE OR THAT THE USE OF MATPLOTLIB 0.98.3 WILL NOT INFRINGE ANY THIRD PARTY RIGHTS.

5. JDH SHALL NOT BE LIABLE TO LICENSEE OR ANY OTHER USERS OF MATPLOTLIB 0.98.3 FOR ANY INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES OR LOSS AS A RESULT OF MODIFYING, DISTRIBUTING, OR OTHERWISE USING MATPLOTLIB 0.98.3, OR ANY DERIVATIVE THEREOF, EVEN IF ADVISED OF THE POSSIBILITY THEREOF.

6. This License Agreement will automatically terminate upon a material breach of its terms and conditions.

7. Nothing in this License Agreement shall be deemed to create any relationship of agency, partnership, or joint venture between JDH and Licensee. This License Agreement does not grant permission to use JDH trademarks or trade name in a trademark sense to endorse or promote products or services of Licensee, or any third party.

8. By copying, installing or otherwise using matplotlib 0.98.3, Licensee agrees to be bound by the terms and conditions of this License Agreement.

```
kindlepdfviewer
===============

This is the former place of http://github.com/koreader/kindlepdfviewer

The development team is very sorry of the inconvenience the renaming causes on your side.
A move to a organization account in GitHub was needed in order to more easily manage issues and permissions for the code base.


Where to find the code now
==========================

As has been said above, the code has moved to a new repository. In fact, it has been splitted and the parts can now be found here:
* *http://github.com/koreader/kindlepdfviewer*

  This is the "legacy" code base. It is a stable reader application with many features, targeted at e-ink reader devices with a *Keyboard*. This includes the Kindle 2, the Kindle DX and the Kindle 3. It will also run on the Kindle 4, but as it expects much more keys, we suggest you have a look at the fork Librerator: http://github.com/kai771/kindlepdfviewer/tree/librerator

* *http://github.com/koreader/koreader*

  This is the former branch for the new UI code, targeting also (for now: only) *touch screen devices* like the Kindle Touch or the Kindle Paperwhite. The branched code was different enough to warrant its own repository.

* *http://github.com/koreader/koreader-base*

  This repository contains the C/C++-to-Lua glue layer, i.e. the API for the native code libraries. It is shared between *koreader* and *KindlePDFviewer*.


About KindlePDFviewer
=====================

KindlePDFviewer is a document viewer application, created for usage on the Kindle e-ink reader. It is currently restricted to 4bpp inverse grayscale displays. For PDF files it is using the muPDF library (see http://mupdf.com/), for DjVu files djvulibre library and for ebooks (fb2, mobi, ePub, etc) crengine. It can also read JPEG images using libjpeg library. The user interface is scripted using Lua (see http://www.lua.org/).

The application is licensed under the GPLv3 (see COPYING file).


Updating your projects
======================

If you forked kindlepdfviewer, you might need to adjust upstream references. Have them point to github.com/koreader/kindlepdfviewer instead of github.com/hwhw/kindlepdfviewer

If you used kindlepdfviewer as a submodule, edit your project's .gitmodules file accordingly.

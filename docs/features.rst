Read the Docs 功能
======================
本文件是 `Read the Docs`_ 所有功能的說明文件。
文件管理中大多數都必須擁有自己說明頁面，您應儘可能的將其功能說明連結頁面，在此列出。

整合 `GitHub`_ 和 `Bitbucket`_ 版本管理器
--------------------------------
目前預設側欄支援連結到您託管主機頁面，應該更能有效的協助 pull 專案或貢獻的人，更快速的得到需求。
更多資訊，請參閱： :doc:`vcs` 頁面。

自動更新
-------------
The :doc:`webhooks` page talks about the different ways you can ping RTD to let us know your project has been updated. We have official support for GitHub, and anywhere else we have a generic post-commit hook that allows you to POST to a URL to get your documentation built.

國際化
--------------------
Read the Docs itself is localized, and we support documentation translated into multiple languages. Read more on the :doc:`localization` and :doc:`i18n` pages.

網址規範
--------------

Canonical URLs give your docs better search performance, by pointing all URLs to one version. This also helps to solve the issues around users landing on outdated versions of documentation.

More information can be found in the :doc:`canonical` page.

版本
--------

We can build multiple versions of your documentation. Look on the "Versions" page
of your project's admin (using the nav on the left) to find a list of available versions
that we've inferred from the tags and branches in your source control system (according to
the support matrix below). On the Versions page you can tell us which versions you'd like us
to build docs for, whether each should be public, protected, or private, and what the default
version should be (we'll redirect there when someone hits your main project page, e.g.,
http://my-project.rtfd.org/).

版本控制器支持表格
-------------------------------
+------------+------------+-----------+------------+-----------+
|            |    Git     |    hg     |   bzr      |     svn   |
+============+============+===========+============+===========+
| Tags       |    Yes     |    Yes    |   Yes      |    No     |
+------------+------------+-----------+------------+-----------+
| Branches   |    Yes     |    Yes    |   Yes      |    No     |
+------------+------------+-----------+------------+-----------+
| Default    |    master  |   default |            |    trunk  |
+------------+------------+-----------+------------+-----------+


PDF 產生 
--------------

When you build your project on RTD, we automatically build a PDF of your project's documentation. We also build them for every version that you upload, so we can host the PDFs of your latest documentation, as well as your latest stable releases as well.

查詢
------

We provide full-text search across all of the pages of documentation hosted on our site. This uses the excellent Haystack project and Solr as the search backend. We hope to be integrating this into the site more fully in the future.

備用域名
-----------------

We provide support for CNAMEs, subdomains, and a shorturl for your project as well. This is outlined in the :doc:`alternate_domains` section.

.. _Read the docs: http://readthedocs.org/
.. _GitHub: https://github.com
.. _bitbucket: https://bitbucket.org/

歡迎來到 Read The Docs
========================

|build-status| |docs|

目的
-------

`Read the Docs`_ 是託管於 `GitHub`_ 開源專案。它支援使用 reStructuredText_ 編輯的 Sphinx_ 文件，您可以從 Subversion_、 Bazaar_、Git_ 和 Mercurial_ 倉庫中 pull，重新編輯後再交回託管。

您可以在 `GitHub`_ 上取回這個專案進行編修。

RTD 說明
---------------------
有關專案設定，請詳閱 `Read the Docs 操作手冊`_ 中的完整說明。

貢獻
------------
在 `貢獻說明`_ 中，提供了如何撰寫 `Read the Docs`_ 的詳細資訊。

GitHub 專案快速託管入門
-------------------------------------
在快速啟動結束之前，您會有一個測試專案 push 到 GitHub。

#. 請在 `Read the Docs 註冊會員`_ 頁面註冊您的帳號後，在七天之內登入到您的信箱，找到驗證信件點擊驗証連結確認您的信箱正確，即完成註冊。
#. 登入 `Read the Docs 專案管理`_ 頁面後點擊 "Import a Project"。
#. Import a Repository 頁面中會有 GitHub 倉庫清單及 "Import Manually" 按鈕，點擊倉庫中的專案選項或 "Import Manually"。
#. 填寫專案的名稱及您在 GitHub 專案倉庫的 HTTPS 連結並選擇 Git 作為倉庫類型。
#. 根據表格內容填寫的其它部分後，點擊 "Create"。
#. 在 GitHub 倉庫導覽列上，點擊 "Settings"。
#. 在側欄中，點擊 "Web Hooks & Services"，然後找到 "ReadTheDocs" 點擊服務。
#. 檢查 "Active" 設定，然後 點擊 "Update Settings"。
#. 完成以上操作後，commit 您的專案後，只要您有編修文件則會自動更新電子書。

.. _Read the docs: http://readthedocs.org/
.. _Read the Docs 註冊會員: https://readthedocs.org/accounts/signup/
.. _Read the Docs 專案管理: https://readthedocs.org/dashboard/
.. _Read the Docs 英文操作手冊: https://docs.readthedocs.io
.. _Read the Docs 操作手冊: http://readthedocs-1.readthedocs.io/zh_TW/latest/

.. _Sphinx: http://sphinx.pocoo.org/
.. _reStructuredText: http://sphinx.pocoo.org/rest.html
.. _Subversion: http://subversion.tigris.org/
.. _Bazaar: http://bazaar.canonical.com/
.. _Git: http://git-scm.com/
.. _Mercurial: https://www.mercurial-scm.org/
.. _GitHub: http://github.com/rtfd/readthedocs.org
.. _貢獻說明: http://docs.readthedocs.io/en/latest/contribute.html#contributing-to-development

.. |build-status_en| image:: https://img.shields.io/travis/rtfd/readthedocs.org.svg?style=flat
    :alt: build status
    :scale: 100%
    :target: https://travis-ci.org/rtfd/readthedocs.org    

.. |docs_en| image:: https://readthedocs.org/projects/docs/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: https://docs.readthedocs.io/en/latest/?badge=latest
    
.. |build-status| image:: https://img.shields.io/travis/rtfd/readthedocs.org.svg?style=flat
    :alt: 建立狀態
    :scale: 100%
    :target: https://travis-ci.org/rtfd/readthedocs.org    
    
.. |docs| image:: https://readthedocs.org/projects/docs/badge/?version=latest
    :alt: 文件狀態
    :scale: 100%
    :target: http://readthedocs-1.readthedocs.io/zh_TW/latest/?badge=latest
             


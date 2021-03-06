---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

title: SQLError
---

SQLError
========

エラー発生時に投げられる `SQLError` オブジェクトです。

プロパティー
----------

- __code:__ 事前に定義された以下のエラーコードのうちの1つを表します
- __message:__ エラーの詳細メッセージを表します

定数
---------

- `SQLError.UNKNOWN_ERR`
- `SQLError.DATABASE_ERR
- `SQLError.VERSION_ERR`
- `SQLError.TOO_LARGE_ERR`
- `SQLError.QUOTA_ERR`
- `SQLError.SYNTAX_ERR`
- `SQLError.CONSTRAINT_ERR`
- `SQLError.TIMEOUT_ERR`

概要
-----------

データベース操作時のエラーに対して投げられる `SQLError` オブジェクトです。


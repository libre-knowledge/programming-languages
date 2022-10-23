# 程式語言<br>Programming languages

用於設計電腦程式的系統化標記集合組成的語言

![「檢查專案中的潛在問題」GitHub Actions 作業流程狀態標章](https://github.com/libre-knowledge/programming-languages/actions/workflows/check-potential-problems.yml/badge.svg "本專案使用 GitHub Actions 自動化檢查專案中的潛在問題") [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "本專案使用 pre-commit 檢查專案中的潛在問題")](https://github.com/pre-commit/pre-commit) [![REUSE 規範遵從狀態標章](https://api.reuse.software/badge/github.com/libre-knowledge/programming-languages "本專案遵從 REUSE 規範降低軟體授權合規成本")](https://api.reuse.software/info/github.com/libre-knowledge/programming-languages)

## 基本概念

### 機器語言<br>Machine language

由指令集(instruction set)組成，可以直接載入中央處理器執行的二進位程式語言，每個不同的處理器家族都有專屬的指令集

由機器語言組成的程式代碼稱為機器碼(machine code)

### 編譯式程式語言<br>Compiled languages

無法直接執行，需要透過編譯器(compiler)、組譯器(assembler)、連結器(linker)等軟體處理過才能夠直接或間接被中央處理器載入並執行的程式語言

有些編譯式程式語言並非直接翻譯為電腦中央處理器的[機器語言](#機器語言machine-language)，而是翻譯為該程式語言執行時期環境的虛擬機(virtual machine)可載入並執行的 byte code 最後再於執行時期由虛擬機翻譯為機器碼執行

常見的編譯式程式語言參閱：[Languages - Compiled language - Wikipedia](https://en.wikipedia.org/wiki/Compiled_language#Languages)

### 直譯式程式語言<br>Interpreted languages

可直接由直譯器(interpreter)在執行時期(runtime)載入並即時翻譯為[機器語言](#機器語言machine-language)程式執行的程式語言

直譯式程式語言通常是人類可讀的語句集合，由該類程式語言設計的程式碼集合常稱為腳本(script)（類比舞台劇中角色使用的劇本）

常見的直譯式程式語言參閱 [Interpreted languages - List of programming languages by type - Wikipedia](https://en.wikipedia.org/wiki/List_of_programming_languages_by_type#Interpreted_languages)

## 解決方案

* Bash
* C
* Go
* Java
* Python
* Ruby
* Rust

## 參考資料

* [程式語言 - 維基百科，自由的百科全書](https://zh.wikipedia.org/wiki/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80)  
  [Programming language - Wikipedia](https://en.wikipedia.org/wiki/Programming_language)  
  說明程式語言的基本概念
* [編譯語言 - 維基百科，自由的百科全書](https://zh.wikipedia.org/zh-tw/%E7%B7%A8%E8%AD%AF%E8%AA%9E%E8%A8%80)  
  [Compiled language - Wikipedia](https://en.wikipedia.org/wiki/Compiled_language)  
  說明編譯式程式語言的概念
* [直譯語言 - 維基百科，自由的百科全書](https://zh.wikipedia.org/zh-tw/%E7%9B%B4%E8%AD%AF%E8%AA%9E%E8%A8%80)  
  [Interpreter (computing) - Wikipedia](https://en.wikipedia.org/wiki/Interpreter_(computing))  
  說明直譯式程式語言的概念
* [機器語言 - 維基百科，自由的百科全書](https://zh.wikipedia.org/wiki/%E6%9C%BA%E5%99%A8%E8%AF%AD%E8%A8%80)  
  [Machine code - Wikipedia](https://en.wikipedia.org/wiki/Machine_code)  
  說明關於機器語言的概念
* [List of programming languages by type - Wikipedia](https://en.wikipedia.org/wiki/List_of_programming_languages_by_type)  
  包含直譯式程式語言的清單


---

本主題為[自由知識協作平台](https://libre-knowledge.github.io/)的一部分，除部份特別標註之經合理使用(fair use)原則使用的內容外允許公眾於授權範圍內自由使用

如有任何問題，歡迎於本主題的[議題追蹤系統](https://github.com/libre-knowledge/programming-languages/issues)創建新議題反饋

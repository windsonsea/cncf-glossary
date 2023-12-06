---
title: 分散式應用程式
status: Completed
category: 概念
tags: ["架構", "", ""]
---

## 是什麼 {#what-it-is}

分散式應用程式是一種功能被拆分為多個較小獨立部分的應用程式。
分散式應用程式通常由獨立的[微服務](/zh-tw/microservices)組成，以處理更廣泛的應用程式中的不同問題。
在雲端原生的環境中，這些獨立元件通常在[叢集](/zh-tw/cluster)中以[容器](/zh-tw/container)執行。

## 解決的問題 {#problem-it-addresses}

在單一計算機上執行的應用程式代表單點故障--如果該台計算機故障，應用程式將變得不可用。
分散式應用程式通常作為[單體式應用程式](/zh-tw/monolithic-apps)的對比。
單體式應用程式可能難以擴展，因為各個元件無法獨立擴展。
隨著單體式應用程式的增長，它們也會拖累開發者的速度，因為更多的開發者需要在未必有明確定義邊界的共享程式碼庫中工作。

## 如何幫助我們 {#how-it-helps}

當將一個應用程式拆分為不同的部分並在許多地方執行，整個系統能夠承受更多的故障。
它也允許應用程式利用單個應用程式實例所不具備的可擴展性，也就是[水平擴展](/zh-tw/horizontal-scaling)。
然而，這也需要付出代價：增加複雜度與營運開銷--你現在正在執行多個應用程式元件，而非單一應用程式。
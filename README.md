---
description: Cấu trúc boilerplate
---

# README

<img src=".gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

```
---------------------------------------src----------------------------------------
NetCoreBoilerplate.Api                  -> Presentation Layer (API)
NetCoreBoilerplate.Application          -> Application Layer
NetCoreBoilerplate.Domain               -> Domain Layer
NetCoreBoilerplate.Infrastructure       -> Infrastructure Layer
--------------------------------------tests-----------------------------------------
NetCoreBoilerplate.Api.Tests            -> Unit Tests for API
NetCoreBoilerplate.Application.Tests    -> Unit Tests for Application Layer
NetCoreBoilerplate.Domain.Tests         -> Unit Tests for Domain Layer
NetCoreBoilerplate.Infrastructure.Tests -> Unit Tests for Infrastructure Layer
------------------------------------sources-----------------------------------------
NetCoreBoilerplate.sln                  -> Solution file
```

## **1. Presentation Layer (**NetCoreBoilerplate**.Api)**

* <mark style="color:green;">**Controllers**</mark>: Chứa các controller để xử lý các request HTTP.
* <mark style="color:green;">**Models**</mark>: Chứa các model để truyền dữ liệu giữa client và server.

## **2. Application Layer (**NetCoreBoilerplate**.Application)**

* <mark style="color:green;">**Services**</mark>: Chứa các dịch vụ ứng dụng để xử lý logic ứng dụng.
* <mark style="color:green;">**DTOs**</mark>: Chứa các đối tượng truyền dữ liệu (Data Transfer Objects).

## **3. Domain Layer (**NetCoreBoilerplate**.Domain)**

* <mark style="color:green;">**Entities**</mark>: Chứa các đối tượng miền (domain objects).
* <mark style="color:green;">**Interfaces**</mark>: Chứa các giao diện cho các repository và dịch vụ miền.
* <mark style="color:green;">**Value Objects**</mark>: Chứa các đối tượng giá trị (value objects).

## **4. Infrastructure Layer (**NetCoreBoilerplate**.Infrastructure)**

* <mark style="color:green;">**Repositories**</mark>: Chứa các lớp thực hiện các repository interface.
* <mark style="color:green;">**Data**</mark>: Chứa các lớp liên quan đến truy cập dữ liệu (ví dụ: DbContext).

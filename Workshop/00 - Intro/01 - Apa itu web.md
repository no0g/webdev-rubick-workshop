# Websites

## Definisi
A set of related web pages located under a single domain name, typically produced by a single person or organization.

**Biasanya static, cuma html**

# Web application

## Definisi
A web application is a computer program that utilizes web browsers and web technology to perform tasks over the Internet.

**Dibikin buat interact sama user, bisa login, read, delete, write, edit data**

# Anatomy web
## Domain/Hostname
Nama yang dipake buat ngerefer ke suatu server yang "menyajikan website".   
Lebih detail di: [Apa itu domain](02%20-%20Server%20dan%20Client.md#apa-itu-domain).

## Subdirectory
Ya intinya web itu kaya files jadi componennya juga folder, di dalam folder ada files.

```
Contoh struktur folder employee management system
.
├── config					|
│   └── config.php			|
├── controller				|  nda return page
│   ├── edit.php			|
│   ├── input.php			|
│   └── remove.php			|
└── employee				}
    ├── edit				}
    │   └── index.php		}	return page 
    ├── index.php			}
    └── input				}
        └── index.php		}

5 directories, 7 files

```


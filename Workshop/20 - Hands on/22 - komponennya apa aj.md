Sesuai dengan [[03 - Web Development#Web App Dev Framework]]
# Model
- Database apu dengan table student dan column data student;


# View
- show all  data (table)
URL = [http:localhost/app/student](http:localhost/student/app/)

- input data
URL = [http://localhost/app/student/input](http://localhost/student/app/input)

- edit data
URL = [http://localhost/app/student/edit](http://localhost/app/student/edit)

# Controller
- input
```sql
insert into student (column, column, column, column) values (?,?,?,?)
```
- edit
```sql
UPDATE student SET COLUMN = ?, COLUMN = ?, COLUMN =? WHERE id = ?

```
- Remove
```sql
DELETE student WHERE id = ?
```

# Subdirectory
```
.
├── config					|
│   └── config.php			|
├── controller				|  nda return page
│   ├── edit.php			|
│   ├── input.php			|
│   └── remove.php			|
└── student					}
    ├── edit				}
    │   └── index.php		}	return page 
    ├── index.php			}
    └── input				}
        └── index.php		}

5 directories, 7 files

```

[prev](https://github.com/no0g/webdev-rubick-workshop/blob/master/Workshop/20%20-%20Hands%20on/21%20-%20Apa%20yg%20kta%20akan%20bikin%3F.md) ---- [next](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
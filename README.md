# iDempiere Demo

## Run

### Start

```
$ docker-compose up -d && docker-compose logs -f
```

### Stop

```
$ docker-compose down
```

## Test

- URL: http://localhost:8080/
- Login: http://localhost:8080/webui/
- User/Password: see [Demo User List](https://wiki.idempiere.org/en/Login_Help#Demo_User_List)


## Notes

- YouTube: [Opensource iDempiere](https://www.youtube.com/channel/UCY_dKpyvNuELgumuwPxYbpw)
- Blog: [มาใช้ ERP iDempiere ฟรีๆ กันดีกว่า Short Introduction and Installation](https://link.medium.com/h62nwxIW7eb)

__Docker Images Size__

```
$ docker images
REPOSITORY                    TAG        IMAGE ID       CREATED        SIZE
idempiereofficial/idempiere   8.2-demo   xxxxxxxxxxxx   23 hours ago   925MB
postgres                      13         xxxxxxxxxxxx   2 days ago     314MB
```

__Database Folder Size__

```
$ du -h -d 0 ./data
553M	./data
```

## References

- [github.com/idempiere/idempiere-docker](https://github.com/idempiere/idempiere-docker)
- [iDempiere Official Docker Image](https://hub.docker.com/r/idempiereofficial/idempiere)

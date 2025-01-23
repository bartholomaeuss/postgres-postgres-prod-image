# POSTGRES/POSTGRES PROD IMAGE

### Prerequisite

```bash
./hello_world.sh
```

### Windows

```bash
./provide_container.sh
```

### More

```
sudo docker run -d --net=host -e POSTGRES_PASSWORD=admin -e POSTGRES_USER=admin -e POSTGRES_DB=test --restart=unless-stopped postgres:test
```

See the official
[duplicati](https://duplicati.readthedocs.io/en/latest/)
documentation.
See also the official
[installation manual](https://duplicati.readthedocs.io/en/latest/02-installation/).
## Container

### Membuat Container

```bash
docker container create --name <nama> -p <port akses>:<port docker> <image docker>
```

Contoh

```bash
docker container create --name server1 -p 8080:80 httpd
```

### Melihat Container Yang Akif

```bash
docker container ls
```

### Melihat Semua Container

```bash
docker container ls --all
```

### Menjalankan Container

```bash
docker container start <nama container>
```

Contoh

```bash
docker container start server1
```

### Stop Container

```bash
docker container stop <nama container>
```

Contoh

```bash
docker container stop server1
```

### Hapus Container

```bash
docker container remove <nama container>
```

Contoh

```bash
docker container remove server1
```

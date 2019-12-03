## docker build
```
docker build -t angular8 .
```

## docker run
```
docker run -it -v `pwd`:/workspace -p 4200:4200 angular8 bash
```

## ng new
```
cd workspace
ng new angular-project
```

## ng serve
```
cd angular-project
ng serve --host 0.0.0.0
```

# alibaba sdk cloudauth written used dara

openapi: https://api.aliyun.com/#/?product=Cloudauth

# use

## install dara

```bash
npm install @darabonba/cli -g

dara config set registry https://darabonba.api.aliyun.com
```

## install deps

```bash
dara install
```

## generate sdk

```bash
# you can refer `dara -h`
dara codegen ts ./ts
```
# netdata

```
curl -fsSL http://my-netdata.io/kivkstart.sh | bash
```

O arquivo de configuração se encontra em

```
vim /etc/netdata/netdata.conf
```

na sessão registry é possivel habilitar para conectar aos outros netdatas dos hosts do 
servidor que está monitorando, para isso, a maquina principal deverá habilitar
a campo enable como yes e o campo registry to announce com o seu ip atual. As demais maquinas
devem utilizar o mesmo ip da principal no campo registry to announce para consegui
integrar ao host netdata principal.

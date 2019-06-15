# esx_bankerjob

## Requisitos

- [cron](https://github.com/ESX-Brasil/cron)
- [esx_addonaccount](https://github.com/ESX-Brasil/esx_addonaccount)
- [esx_society](https://github.com/ESX-Brasil/esx_society)

## Download e Instalação

### Usando o [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx ESX-Brasil/esx_bankerjob
```

### Usando o Git
```
cd resources
git clone https://github.com/ESX-Brasil/esx_bankerjob [esx]/esx_bankerjob
```

### Manualmente
- Download https://github.com/ESX-Brasil/esx_bankerjob/archive/master.zip
- Coloque-o no diretório `[esx]`

## Instalação
- Importe `esx_bankerjob.sql` em seu banco de dados
- Adicione isto em seu `server.cfg`:

```
start esx_bankerjob
```

# Legal
### License
esx_bankerjob - bank script

Copyright (C) 2015-2019 ESX-Brasil

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.

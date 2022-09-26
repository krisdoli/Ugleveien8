import tablemark from "tablemark"
<h1 align="center">
  <a name="logo" href="#"><img src="https://github.com/krisdoli/Ugleveien8/blob/main/ugleveien8smarthjem.png" alt="Ugleveien8 Smarthjem" width="200"></a>
  <br>
  Ugleveien8 Smarthjem dokumentasjon
</h1>
<h4 align="center">Sørg for å :star: min konfigurasjonsrepo, slik at du kan holde deg oppdatert på enhver daglig fremgang!</h4>

| UPS          | pri Bredbånd  | sec Bredbånd | Server, router |  Network backbone  |
| :-:          | :-:           | :-:          | :-:            | :-: |
| git status   | Altibox fiber |              | Proxmox VM     |  Ubiquiti UniFi US-8-60W Switch |
| git diff     |    git diff   |              | lenovo thinkcentre  | |
|              |               |              | - PfSense, Home assistant OS, HomeKit Bridge ||

tablemark([
  { name: "Bob", age: 21, isCool: false },
  { name: "Sarah", age: 22, isCool: true },
  { name: "Lee", age: 23, isCool: true }
], {
  columns: [
    "first name",
    { name: "how old", align: "center" },
    "are they cool"
  ]
})

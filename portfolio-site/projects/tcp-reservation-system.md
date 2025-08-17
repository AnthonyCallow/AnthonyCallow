
# TCP Reservation System (C#)

**Stack:** .NET, C#, TCP sockets, ADO.NET, JSON, SQL Server

**What I built**
- Multithreaded TCP server with a **max 5 clients** limit
- Thread-safe **inventory updates** to avoid overselling
- Client GUI to browse stores and reserve games
- JSON protocol with request/response types

**Key Files**
- `ServidorTCP.cs` — connection handling, validation, thread limits
- `FrmReserva` — client UI that lists stores/games and shows reservations

**Highlights**
- Implemented `ValidarCliente`, `ObtenerTiendas`, `ObtenerVideojuegos`, `ConsultarReservas`, `ConsultarReservaPorId`
- Demonstrated use of `lock` / synchronization for shared resources

**Screenshots**
_Add images under `/assets/img/` and link them here._

**Repo:** link-here

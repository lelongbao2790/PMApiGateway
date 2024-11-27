To config ocelot.
Open config.ocelot.development.json or config.ocelot.Docker.json or config.ocelot.Production.json

Put every service for routing in group 
{
Upstream // The incoming request 
Downstream // The outcoming after receive incoming from upstream
}
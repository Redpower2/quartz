```mermaid
flowchart BT

Ent[("Entidades")]
	It[/ "Items" /]
		Tien[["Tiendas"]]
	Tec[/ "Técnicas" /]
	
PJ[("Personajes")]
	Inv(["Inventario"])
	Alias(["Alias"])
	ID(["ID"])
	UId(["UserId"])
	Bil(["Billetera"])

Users[("Usuarios")]

Mon[("Monedas")]
	Tael["Tael (nacional)"]
	Bor["Borbón (local)"]
	Mint["Monedas internacionales"]

Inst[("Instituciones")]
	Prin[/ "Principado" /]
	Ban[/ "Bancos" /]
		BanCe["Banco central"]
	Emp[/ "Empresas" /]

Prop[("Propiedades")]
	Viv[/ "Viviendas" /]
	Neg[/ "Negocios" /]


Ent --> It
	It -.-> Tien
Ent --> Tec

PJ --> Inv
	It -.-> Inv
PJ --> Alias
PJ --> ID
PJ --> Bil
PJ --> UId
	UId -.-> Users

Mon --> Tael
	Tael -.-> Bil
Mon --> Bor
	Bor -.-> Bil
Mon --> Mint
	Mint -.-> Bil

Inst --> Prin
Inst --> Ban
	Ban --> BanCe
		BanCe -.-> Bor
Inst --> Emp

Prop --> Viv
Prop --> Neg
	Emp --> Neg
```


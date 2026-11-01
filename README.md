# Mozambique Land Rights & DUAT Lookup MCP (Moçambique)

[Português](#português)

Connect your AI assistant (Claude, ChatGPT, Cursor) to [BumiAtlas](https://bumiatlas.com) for Mozambican land research through the Model Context Protocol (MCP).

This listing is a focused entry point for:

- ~329k registered DUATs (Direito de Uso e Aproveitamento da Terra, the registered right to use State land) from FNDS, with province, district, the holder's sex, stated purpose and area
- ~6.6k community land delimitations under the 1997 Land Law, and ~19.8k SIDICA community-land parcels from customary-tenure projects (Terra Firma)
- Lookup of everything at a point, communities by name, and SIDICA parcels by UPI
- Satellite and street map images of the DUATs around a point

No holder names. DUAT boundaries are often sketched, not surveyed.

## Connect

```
https://bumiatlas.com/mcp/mozambique
```

Add it as a custom connector in any MCP client and sign in with Google. Tools, examples and data notes: [bumiatlas.com/mcp-docs/mozambique](https://bumiatlas.com/mcp-docs/mozambique).

- **Claude:** Settings → Connectors → Add custom connector, paste the URL, then Connect.
- **ChatGPT:** Settings → Apps & Connectors → Advanced → Developer mode, then Create with the URL and OAuth authentication.

## Tools

| Tool | Description |
|---|---|
| `MZ_land_search` | DUATs, SIDICA parcels and community delimitations at `latitude, longitude`, communities by name (paged), or SIDICA parcels by UPI; each record whole, boundaries as GeoJSON on request |
| `MZ_duat_image` | Satellite or street map image of a DUAT or point, with every DUAT in view outlined and labelled with its stated purpose |

## Example prompts

- *"What land rights are registered at -25.9692, 32.5732?"*
- *"Is this point inside a delimited community? Which one?"*
- *"Show the DUATs around this point on satellite imagery."*
- *"What are the DUATs here used for, and how large are they?"*

## Data source

DUATs and community delimitations © FNDS (Fundo Nacional de Desenvolvimento Sustentável), Mozambique; SIDICA parcels © Terra Firma. A copy of public data for research, not a legal land record.

## Português

Ligue o seu assistente de IA (Claude, ChatGPT ou Cursor) ao [BumiAtlas](https://bumiatlas.com) através do Model Context Protocol (MCP) para pesquisar a terra em Moçambique.

- ~329 mil DUAT registados (FNDS), com província, distrito, sexo do titular, finalidade e área
- ~6,6 mil delimitações de comunidades e ~19,8 mil parcelas comunitárias do SIDICA
- Pesquisa por coordenadas, nome da comunidade ou UPI, com imagens de satélite e mapas

Sem nomes de titulares.

**Ligação:** adicione `https://bumiatlas.com/mcp/mozambique` como conector personalizado no seu cliente MCP e inicie sessão com o Google. Os nomes das ferramentas estão em inglês, mas o assistente pode responder em português.

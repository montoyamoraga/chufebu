# chufebu

## About

chufebu is an open source hardware Eurorack power bus board by [piruetas](https://piruetas.xyz). It distributes ±12V, +5V, CV and GATE to five 16-pin Eurorack power headers, each one paired with its own 4-pin Molex KK-396 connector for testing. The design is made in KiCad 10 using only KiCad's standard libraries. Hardware is licensed under CERN-OHL-P-2.0 and documentation under CC-BY-SA-4.0 (see [LICENSE.md](./LICENSE.md)). Documentation, schematic, board render and bill of materials (in Spanish): <https://piruetas.xyz/chufebu/>.

## Acerca de

Bus de alimentación eurorack de [piruetas](https://piruetas.xyz), hecho en KiCad y publicado como hardware de código abierto.

Documentación, esquemático, placa y Bill of materials: <https://piruetas.xyz/chufebu/>.

## Características

- 5 headers de alimentación Eurorack de 16 pines (2x08), conectados en bus.
- Cada header tiene su conector Molex KK-396 de 4 pines, para pruebas: -12V, GND, +5V y +12V.
- Las líneas CV y GATE también van en bus entre los 5 headers.
- Placa de 100 × 45 mm, 2 capas, con 2 agujeros de montaje M3.
- Solamente usa las bibliotecas estándar de KiCad 10: no hace falta instalar bibliotecas adicionales para abrir o modificar el diseño.

## Pines y manual de uso

Los pines de los headers de 16 pines y de los conectores KK-396, cómo conectar chufebu y las advertencias están en el [manual de uso](https://piruetas.xyz/chufebu/#manual-de-uso).

## Revisiones

- `v0.1 rev-a`: fabricada en octubre 2026, todavía sin probar.

## Estructura del repositorio

- [hardware/chufebu-v-0-rev-a](./hardware/chufebu-v-0-rev-a): proyecto de KiCad (esquemático y placa), los archivos fuente del diseño.
- [hardware/chufebu-v-0-rev-a-fab](./hardware/chufebu-v-0-rev-a-fab): gerbers y archivos de taladrado para fabricar la placa.
- [docs](./docs): documentación, publicada en <https://piruetas.xyz/chufebu/>. Las capturas del esquemático y de la placa, y la tabla de Bill of materials, las genera [kicad-retrata](https://github.com/piruetasxyz/kicad-retrata) en cada push (ver [kicad-retrata.yml](./kicad-retrata.yml)).
- [LICENSES](./LICENSES): textos completos de las licencias.

## Fabricación

piruetas vende chufebu armado y probado.

Como es hardware de código abierto, los archivos fuente de KiCad, los archivos de fabricación de [hardware/chufebu-v-0-rev-a-fab](./hardware/chufebu-v-0-rev-a-fab) y la [Bill of materials](https://piruetas.xyz/chufebu/#bill-of-materials-v01-rev-a) están publicados para que cualquiera pueda estudiar, modificar y fabricar el diseño. piruetas no da soporte para unidades fabricadas o armadas por terceros.

## Licencia

chufebu es (c) 2026 piruetas SpA / Aarón Montoya-Moraga.

- Hardware (`hardware/`): [CERN-OHL-P-2.0](./LICENSES/CERN-OHL-P-2.0.txt).
- Documentación (`docs/`): [CC-BY-SA-4.0](./LICENSES/CC-BY-SA-4.0.txt).
- El nombre, logo y marca de piruetas no están cubiertos por estas licencias: ver [LicenseRef-piruetas-branding](./LICENSES/LicenseRef-piruetas-branding.txt).

Ver [LICENSE.md](./LICENSE.md) para los detalles. El repositorio sigue la especificación [REUSE](https://reuse.software/).

# chufebu

## About

chufebu is an open source hardware Eurorack power bus board by [piruetas](https://piruetas.xyz). It distributes ±12V, +5V, CV and GATE to five 16-pin Eurorack power headers. The design is made in KiCad 10 using only KiCad's standard libraries. Hardware is licensed under CERN-OHL-P-2.0 and documentation under CC-BY-SA-4.0 (see [LICENSE.md](./LICENSE.md)). Documentation, schematic, board render and bill of materials (in Spanish): <https://piruetas.xyz/chufebu/>.

## Acerca de

Bus de alimentación eurorack de [piruetas](https://piruetas.xyz), hecho en KiCad y publicado como hardware de código abierto.

Documentación, esquemático, placa y Bill of materials: <https://piruetas.xyz/chufebu/>.

## Características

- 5 headers de alimentación Eurorack de 16 pines (2x08), conectados en bus.
- Las líneas CV y GATE también van en bus entre los 5 headers.
- Placa de 100 × 40 mm, 2 capas, con 4 agujeros de montaje M3.
- Solamente usa las bibliotecas estándar de KiCad 10: no hace falta instalar bibliotecas adicionales para abrir o modificar el diseño.

## Pines y manual de uso

Los pines de los headers de 16 pines, cómo conectar chufebu y las advertencias están en el [manual de uso](https://piruetas.xyz/chufebu/#manual-de-uso).

## Revisiones

- `v0.1 rev-b`: fabricada y probada en noviembre 2026. Sin conectores Molex KK-396, placa de 100 × 40 mm y 4 agujeros de montaje M3.
- `v0.1 rev-a`: fabricada en octubre 2026, probada y funciona. Incluía 5 conectores Molex KK-396 de 4 pines.

## Estructura del repositorio

- [hardware/chufebu-v-0-rev-b](./hardware/chufebu-v-0-rev-b): proyecto de KiCad (esquemático y placa) de la revisión actual, los archivos fuente del diseño.
- [hardware/chufebu-v-0-rev-b-fab](./hardware/chufebu-v-0-rev-b-fab): gerbers y archivos de taladrado para fabricar la placa de la revisión actual.
- [hardware/chufebu-v-0-rev-a](./hardware/chufebu-v-0-rev-a) y [hardware/chufebu-v-0-rev-a-fab](./hardware/chufebu-v-0-rev-a-fab): revisión anterior.
- [docs](./docs): documentación, publicada en <https://piruetas.xyz/chufebu/>. Las capturas del esquemático y de la placa, y la tabla de Bill of materials, las genera [kicad-retrata](https://github.com/piruetasxyz/kicad-retrata) en cada push (ver [kicad-retrata.yml](./kicad-retrata.yml)).
- [LICENSES](./LICENSES): textos completos de las licencias.

## Fabricación

piruetas vende chufebu armado y probado.

Como es hardware de código abierto, los archivos fuente de KiCad, los archivos de fabricación de [hardware/chufebu-v-0-rev-b-fab](./hardware/chufebu-v-0-rev-b-fab) y la [Bill of materials](https://piruetas.xyz/chufebu/#bill-of-materials-v01-rev-b) están publicados para que cualquiera pueda estudiar, modificar y fabricar el diseño. piruetas no da soporte para unidades fabricadas o armadas por terceros.

## Créditos

- Aarón Montoya-Moraga: investigación, esquemático, PCB, fabricación y documentación.
- Matías Serrano: revisor experto de esquemáticos y PCBs.

## Licencia

chufebu es (c) 2026 piruetas SpA / Aarón Montoya-Moraga.

- Hardware (`hardware/`): [CERN-OHL-P-2.0](./LICENSES/CERN-OHL-P-2.0.txt).
- Documentación (`docs/`): [CC-BY-SA-4.0](./LICENSES/CC-BY-SA-4.0.txt).
- El nombre, logo y marca de piruetas no están cubiertos por estas licencias: ver [LicenseRef-piruetas-branding](./LICENSES/LicenseRef-piruetas-branding.txt).

Ver [LICENSE.md](./LICENSE.md) para los detalles. El repositorio sigue la especificación [REUSE](https://reuse.software/).

swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListMICToLegacyExchange:
    get:
      summary: List MIC To Legacy Exchange
      description: Get the legacy exchanges.
      operationId: ListMICToLegacyExchange
      x-api-path-slug: listmictolegacyexchange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - MIC
      - Legacy
      - Exchange
  /ListMICToLegacySuffix:
    get:
      summary: List MIC To Legacy Suffix
      description: Get the legacy exchange suffix.
      operationId: ListMICToLegacySuffix
      x-api-path-slug: listmictolegacysuffix-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - MIC
      - Legacy
      - Suffix
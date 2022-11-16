Popis je u JSON formatu.

DB schema:

```
model Naselja {
  id                     Int    @id @default(autoincrement()) @db.MediumInt
  NASELJE_MBR            Int
  NASELJE_NAZIV          String @db.VarChar(40)
  GROP_MBR               Int
  GROP_NAZIV             String @db.VarChar(50)
  NASELJE_POSTANSKI_BROJ Int
  ZUPANIJA_MBR           Int
  ZUPANIJA_NAZIV         String @db.VarChar(40)
}
```

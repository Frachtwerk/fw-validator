# fw-validator

[![Quality gate status](https://sonarcloud.io/api/project_badges/measure?project=Frachtwerk_fw-validator&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Frachtwerk_fw-validator)

## Build

```
mvn verify
```

Java 21. `mvn verify` prüft auch die Formatierung (google-java-format) und die Lizenz-Header;
`mvn spotless:apply` formatiert den Code und ergänzt fehlende Header.

## Lizenz

fw-validator steht unter der GNU Lesser General Public License v3 oder (nach Wahl) einer späteren Version,
siehe [LICENSE](LICENSE). Die LGPL ergänzt die GNU General Public License v3, deren Text in
[COPYING](COPYING) liegt.

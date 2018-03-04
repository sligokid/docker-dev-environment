docker run --rm -v $(pwd)/sql:/flyway/sql boxfuse/flyway -url=jdbc:h2:mem:test -user=sa migrate

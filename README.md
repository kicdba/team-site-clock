# team-site-clock

Once an hour, a GitHub Actions job asks a private team tool whether any
notifications are due. The tool's address is kept in a repository secret, and the
job prints nothing but the answer's status code.

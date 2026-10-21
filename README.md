# team-site-clock

Once an hour, a GitHub Actions job asks a private team tool whether any
notifications are due. The tool's address is kept in a repository secret, and the
job prints nothing but the answer's status code. The schedule stops on its own once
the tool is no longer used: a weekly step keeps it on only while someone has opened
the tool in the last 30 days.

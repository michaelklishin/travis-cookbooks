Current:

- Added Erlang R16B03 (Michael Klishin)
- Cassandra 2.0.4 (Michael Klishin)
- ElasticSearch 0.9.10 (Ray Ward)
- Update Gradle to 1.10 (Michael Klishin)
- Update Perl versions to 5.17.11, 5.18.1 and 5.19.6 (Henrik Hodne)

Production .org 10.12.2013

- Fix rvm warning that a Ruby version can't be found even though it's available (Josh Kalderimis)

- Update Redis to 2.8.2 (currently only on the Ruby, PHP and JVM images) (Josh Kalderimis)

- Raise PHP memory limit to 1GB (Loïc Frering)

- Add Go 1.2 to preinstalled versions (Mathias Meyer)

- Download Cassandra from Apache archive (Michael Klishin)

Production .org and .com 29.11.2013:

- Update RVM to 1.24.5 (Josh Kalderimis)
  This will include updated checksums for Ruby 1.9.3 (p484) and changes to
  how RBX is selected.

- Update Leiningen to 2.3.4 (Michael Klishin)

- Update Ruby 1.9.3-p484 and 2.0.0-p353 (Josh Kalderimis)

- Update Node.js 0.11 branch to 0.11.9 (Josh Kalderimis)

- Update Cassandra to 2.0.3 (Josh Kalderimis)

- Update Gradle to 1.9 (Michael Klishin)

- Update Cassandra configurations for 2.0.2 (#242, Mathias Meyer)
  The last update broke Cassandra completely by using older versions of the
  configurations. This change removes any special cases, as 2.0.2 runs just fine
  on our default stack with IPv4 now.

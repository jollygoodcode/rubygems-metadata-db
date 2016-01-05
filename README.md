# RubyGems Metadata Database

The RubyGems Metadata Database aims to provide all rubygems' metadata in JSON format for automated tools to consume.

## Directory Structure

The database is a list of directories that match the names of Ruby libraries on https://rubygems.org. Within each directory is one json file (`metadata.json`) for the Ruby library, for example:

```
gems/:
  rails/:
    metadata.json
```

## Format

Each metadata file contains the information in JSON format, for example, the pg gem:

```json
{
  "name": "pg",
  "full_repo_name": "ged/ruby-pg",
  "gem_uri": "https://rubygems.org/gems/pg-0.18.4.gem",
  "wiki_uri": "http://bitbucket.org/ged/ruby-pg/wiki/Home",
  "project_uri": "https://rubygems.org/gems/pg",
  "homepage_uri": "https://bitbucket.org/ged/ruby-pg",
  "bug_tracker_uri": "https://bitbucket.org/ged/ruby-pg/wiki/Submitting%20Tickets",
  "source_code_uri": "http://bitbucket.org/ged/ruby-pg/",
  "mailing_list_uri": "https://groups.google.com/forum/?hl=en\u0026fromgroups#!forum/ruby-pg",
  "documentation_uri": "http://deveiate.org/code/pg/",
  "changelog_uri": "https://github.com/ged/ruby-pg/blob/master/History.rdoc"
}
```

## Credits

Thanks to all our [contributors](https://github.com/jollygoodcode/rubygems-metadata-db/graphs/contributors)!

Inspired by [rubysec/ruby-advisory-db](https://github.com/rubysec/ruby-advisory-db).

## License

### CC0 1.0 Universal

To the extent possible under law, we waived all copyright and related or neighboring rights to "rubygems-metadata-db". If you submit code or data to the ruby-advisory-db that is copyrighted by yourself, upon submission you hereby agree to release it into the public domain.

## Maintained by Jolly Good Code

[![Jolly Good Code](https://cloud.githubusercontent.com/assets/1000669/9362336/72f9c406-46d2-11e5-94de-5060e83fcf83.jpg)](http://www.jollygoodcode.com)

We specialise in Agile practices and Ruby, and we love contributing to open source.
[Speak to us](http://www.jollygoodcode.com/#get-in-touch) about your next big idea, or [check out our projects](http://www.jollygoodcode.com/open-source).

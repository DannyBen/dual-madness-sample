# Dual Madness Example

This is an example repo for https://github.com/DannyBen/madness/issues/143

It shows how to run the Markdown Madness server under a subpath, and how
to run multiple madness servers under the same domain.

## Usage

1. Clone the repository
2. Run `docker-compose pull`
3. Run `docker-compose up one two`
4. Go to <http://madness.localhost/one> and <http://madness.localhost/two>

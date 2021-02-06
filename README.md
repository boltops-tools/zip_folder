# ZipFolder

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Zip folder up. Just took this [example](https://github.com/rubyzip/rubyzip/blob/master/samples/example_recursive.rb) and packaged it as a gem.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'zip_folder'
```

## Usage

```ruby
ZipFolder.zip(input_dir, output_file)
ZipFolder.zip("/path/to/folder", "/path/to/file.zip")
```


# Custard

Custard is a useful CSS preset to reduce coding of CSS.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'custard'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install custard

## Usage

If you want the following styles.

when

```html
<div style="
  border-top: 1px solid #666;
  border-bottom: 1px solid #666;
"></div>
```
that

```html
<div class="bdr-tb-1px-gray6">
```

when

```html
<div style="
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -ms-flex-pack: end;
  -webkit-justify-content: flex-end;
  -moz-justify-content: flex-end;
  justify-content: flex-end;
  -ms-flex-align: center;
  -webkit-align-items: center;
  -moz-align-items: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  -webkit-flex-wrap: wrap;
  -o-flex-wrap: wrap;
  -moz-flex-wrap: wrap;
  flex-wrap: wrap;
"></div>
```

that

```html
<div class="ds-flex-right-center-wrap"></div>
```

when

```html
<div style="
  margin-top: 10px;
  margin-bottom: 10px;
  margin-left: 10px;
"></div>
```

that

```html
<div class="mgn-tbl-10px"></div>
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/custard/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

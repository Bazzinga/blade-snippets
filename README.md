# Blade Snippets for Sublime Text

`Blade` is a simple, yet powerful templating engine provided with [Laravel] (http://laravel.com) PHP framework.

These snippets works with blade files (`.blade.php`) either with php syntax or with blade syntax using: **PHP - Laravel Blade** available from [Laravel Blade Highlighter] (https://github.com/Medalink/laravel-blade) package.

##Usage
When you're on a blade file, type the snippet shortcut then press `tab` key.

##Installation
Via `Package Manager` search for `Blade Snippets` then click/tap…wait a sec and tadam!

![Blade Snippets](http://f.dev.mk.ua/files/dadbee44b4461b709d444951ba26f70f/file_51d27202c2a8b.png)

Or clone this repository into your Packages folder:

    git clone https://github.com/dev4dev/blade-snippets.git


Or download the snippets zip file and unzip it into your Packages folder.

##Avalable snippets
<table>
	<tr>
		<th>Shortcut</th>
		<th>Result</th>
	</tr>
	<tr>
		<td>ext</td>
		<td>
		@extends('`name`')
		</td>
	</tr>
	<tr>
		<td>lay</td>
		<td>
		@layout('`name`')
		</td>
	</tr>
	<tr>
		<td>sec</td>
		<td>
		@section('`name`')
		<br><br>
		@endsection
		</td>
	</tr>
	<tr>
		<td>secy</td>
		<td>
		@section('`name`')
		<br><br>
		@yield_section
		</td>
	</tr>
	<tr>
		<td>yl</td>
		<td>
		@yield('`section`', '`default`')
		</td>
	</tr>
	<tr>
		<td>par</td>
		<td>
		@parent
		</td>
	</tr>
	<tr>
		<td>}}</td>
		<td>
		{{ $`var` }}
		</td>
	</tr>
	<tr>
		<td>}}}</td>
		<td>
		{{ `expression` }}
		</td>
	</tr>
	<tr>
		<td>inc</td>
		<td>
		@include('`view.name`', `array('some' => 'data')`)
		</td>
	</tr>
	<tr>
		<td>if</td>
		<td>
		@if (`condition`)
		<br><br>
		@endif
		</td>
	</tr>
	<tr>
		<td>ife</td>
		<td>
		@if (`condition`)
		<br><br>
		@else
		<br><br>
		@endif
		</td>
	</tr>
	<tr>
		<td>foreach</td>
		<td>
		@foreach(`$array` as `$element`)
		<br><br>
		@endforeach
		</td>
	</tr>
	<tr>
		<td>fore</td>
		<td>
		@forelse (`$array` as `$element`)
		<br><br>
		@endforelse
		</td>
	</tr>
	<tr>
		<td>for</td>
		<td>
		@for (`$i` = `0`; `$i` `<` `…`; `$i++`)
		<br><br>
		@endfor
		</td>
	</tr>
	<tr>
		<td>trans</td>
		<td>
		{{ trans('language.line') }}
		</td>
	</tr>
	<tr>
		<td>route</td>
		<td>
		{{ route('name') }}
		</td>
	</tr>
	<tr>
		<td>asset</td>
		<td>
		{{ asset('path') }}
		</td>
	</tr>
	<tr>
		<td>while</td>
		<td>
		@while (`condition`)
		<br><br>
		@endwhile
		</td>
	</tr>
	<tr>
		<td>unless</td>
		<td>
		@unless (`condition`)
		<br><br>
		@endunless
		</td>
	</tr>
	</table>


---
Original snippets by:
[@dev4dev](https://github.com/dev4dev)

Cool Readme formatting and latest updates belong to:
* Github: [@AAlakkad](https://github.com/AAlakkad).
* Twitter: [@Am_Alakkad](https://twitter.com/Am_Alakkad).
* Email: [am.alakkad@gmail.com] (mailto:am.alakkad@gmail.com).

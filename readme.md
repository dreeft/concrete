#	Concrete

A simple, responsive, 12 column grid - nothing more.

##	Usage

###	Rows

A row is a horizontal representation which contains columns.

	<div class="row">
	</div>

###	Columns

A column can be defined by defining the class with the keyword `column` or `columns` and the width (e.g. `one`, `two`, `twelve`).

	<div class="row">
		<section class="three columns">
		</section>
		
		<section class="six columns">
		</section>
		
		<section class="three columns">
		</section>
	</div>

###	Offsets

Columns can be offset by a certain number of columns by defining the class with the keyword `offset` and the offset amount (e.g. `by-one`, `by-two`, `by-eleven`).

	<div class="row">
		<section class="four columns offset by-three">
		</section>
		
		<section class="two columns">
		</section>
	</div>

###	Nested Columns

Columns can be nested one level deep by placing them within another column.

	<div class="row">
		<section class="nine columns">
			<section class="four columns">
			</section>
			<section class="five columns">
			</section>
		</section>
		
		<section class="three columns">
		</section>
	</div>

##	Responsive Behaviour

At desktop resolutions, the full 960px grid will be displayed. At tablet resolutions, the grid will be compressed to a 720px grid. At mobile resolutions, the grid will be compressed to a single column.
# Klassen, Objekte und Variablen #

# Klasse Produkt #

	@@@ ruby
	class Product
	end

	product = Product.new
	#=> #<Product:0x007fcc510c1aa0>

# Initialize #

	@@@ ruby
	class Product
		def initialize
			puts "Product#initialize"
		end
	end

	product = Product.new
	# "Product#initialize"

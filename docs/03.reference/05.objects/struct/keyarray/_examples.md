
```luceescript+trycf
animals = {
	cow: "moo",
	pig: "oink",
	cat: "meow",
	bird: "chirp"
};
// animals.keyArray()
animalKeyArray = animals.keyArray();
// Show results of animalKeyArray
// ["bird","cat","cow","pig"]
dump(animalkeyarray);
for (animal in animalKeyArray) {
	// Show value of animal in animals
	Dump(
		label: "Value of " & animal,
		var: animals[animal]
	);
}
```
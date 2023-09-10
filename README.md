# ILOC Frontend Tests

Test blocks for lab 1 of COMP 412 at Rice University. Extracted from my unit tests.

See [`ref-stderr/`](./ref-stderr/) for the stderr outputs of the reference solution (version "COMP 412, Fall 2020, Front End  (lab1_ref)").

```sh
cd blocks
for block in *.i
	~comp412/students/lab1/lab1_ref -p $block 2> ../ref-stderr/$block.out
end
```

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

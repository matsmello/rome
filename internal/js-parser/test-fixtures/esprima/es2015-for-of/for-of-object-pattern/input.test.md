# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-for-of > for-of-object-pattern`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSForOfStatement {
			await: false
			loc: Object {
				filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSEmptyStatement {
				loc: Object {
					filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 17
						line: 1
					}
				}
			}
			right: JSReferenceIdentifier {
				name: "z"
				loc: Object {
					filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
					identifierName: "z"
					end: Object {
						column: 16
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
			left: JSAssignmentObjectPattern {
				rest: undefined
				loc: Object {
					filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
				properties: Array [
					JSAssignmentObjectPatternProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
									identifierName: "x"
									end: Object {
										column: 7
										line: 1
									}
									start: Object {
										column: 6
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 6
									line: 1
								}
							}
						}
						value: JSAssignmentIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
								identifierName: "x"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 6
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
							end: Object {
								column: 7
								line: 1
							}
							start: Object {
								column: 6
								line: 1
							}
						}
					}
					JSAssignmentObjectPatternProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "y"
								loc: Object {
									filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
									identifierName: "y"
									end: Object {
										column: 10
										line: 1
									}
									start: Object {
										column: 9
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						value: JSAssignmentIdentifier {
							name: "y"
							loc: Object {
								filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
								identifierName: "y"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-for-of/for-of-object-pattern/input.js"
							end: Object {
								column: 10
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```

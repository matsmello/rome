# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 197`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/197/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/197/input.js"
		end: Object {
			column: 26
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSDoWhileStatement {
			loc: Object {
				filename: "es2015/uncategorised/197/input.js"
				end: Object {
					column: 19
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			test: JSBooleanLiteral {
				value: false
				loc: Object {
					filename: "es2015/uncategorised/197/input.js"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 13
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2015/uncategorised/197/input.js"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 3
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/197/input.js"
				end: Object {
					column: 26
					line: 1
				}
				start: Object {
					column: 20
					line: 1
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "es2015/uncategorised/197/input.js"
					end: Object {
						column: 25
						line: 1
					}
					start: Object {
						column: 20
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "es2015/uncategorised/197/input.js"
						identifierName: "foo"
						end: Object {
							column: 23
							line: 1
						}
						start: Object {
							column: 20
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```

# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-module > invalid-commonjs-module`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 88
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FlowDeclareModule {
      id: StringLiteral {
        value: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 20
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
      }
      kind: 'commonjs'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 87
          index: 87
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 87
            index: 87
            line: 1
          }
          start: Object {
            column: 21
            index: 21
            line: 1
          }
        }
        body: Array [
          FlowDeclareModuleExports {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 54
                index: 54
                line: 1
              }
              start: Object {
                column: 23
                index: 23
                line: 1
              }
            }
            typeAnnotation: NumberKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 53
                  index: 53
                  line: 1
                }
                start: Object {
                  column: 47
                  index: 47
                  line: 1
                }
              }
            }
          }
          FlowDeclareExportNamed {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 84
                index: 84
                line: 1
              }
              start: Object {
                column: 55
                index: 55
                line: 1
              }
            }
            declaration: FlowDeclareVariable {
              id: BindingIdentifier {
                name: 'a'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 83
                    index: 83
                    line: 1
                  }
                  start: Object {
                    column: 74
                    index: 74
                    line: 1
                  }
                }
                meta: PatternMeta {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 83
                      index: 83
                      line: 1
                    }
                    start: Object {
                      column: 74
                      index: 74
                      line: 1
                    }
                  }
                  typeAnnotation: NumberKeywordTypeAnnotation {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 83
                        index: 83
                        line: 1
                      }
                      start: Object {
                        column: 77
                        index: 77
                        line: 1
                      }
                    }
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 84
                  index: 84
                  line: 1
                }
                start: Object {
                  column: 70
                  index: 70
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
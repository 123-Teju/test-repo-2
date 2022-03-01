# test-repo-2
const { division } = require('./division')
test ('2/2=0' , () => {
expect(division(2,2)).toBe(1)
})
const division = (a,b) => a%b;

module.export = (division)

# CSS tricks

## ſelectors

### pſeudoclaſses
- `:hover` ƕen ðe mouse is on ðe element
- `:active` during ðe short time in ƕich ðe click is maintained, may noȝt be noticeable
- `:visited` obviously, it is an already visited link

### advanced ſelectors
- `A + B` ſelects only ðe element B ðat follows an element A
- `A > B` ſelects only ðe element B contained in an element A
- `A, B` ſelects all A and B to set ðem common properties

- `A[*attribute*]` ſelects only A elements ƕich have ðis type of attribute
- `A[*attribute*="*value*"]` ſelects only A elements ƕich have ðis exact value
> ◇　`A[id="*identifier*"]` is a ſtupid way of ſaying `#*identifier*`


## options
- `box-sizing: border-box;` takes ðe border widð in box ſize
- `box/text-shadow: *x-offſet* *y-offſet* *smooð*　*colour*;` ðe order is important

## about `background`
- `linear-gradient()` default direction is top to bottom.
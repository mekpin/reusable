# reusable workflow


uses itu me utilisasi worfklow yml dari repo lain (action tetap ada di repo awal)
with itu ngebawa variable dr repo sebelumnya ke dalam input repo "uses"

call output 
between steps: inside the same jobs steps.{id}.outputs.{name (before "=")}
between jobs: needs.{jobs-name}.outputs.{name (before ":")}
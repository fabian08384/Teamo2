# Teamo2
const love = ['❤', '❤', '❤', '❤']
let ourLove = 10000

const isNoteLove = love.some(notLove => notLove === '💔')

while (isNotLove !== true) {
  ourLove ++
  love.push('❤')
}

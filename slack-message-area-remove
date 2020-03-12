function removeMessageArea(timeout = 5000, intervalTime = 500) {
	if (timeout < intervalTime) {
		timeout = 5000
		intervalTime = 500
	}
	const count = Math.floor(timeout / intervalTime)
	const intervalId = window.setInterval(function() {
		if (document.querySelector('#c-coachmark-anchor') !== undefined) {
			document.querySelector('#c-coachmark-anchor').remove()
			clearInterval(intervalId)
		}
		if (--count < 0) {
      clearInterval(intervalId)
    }
  }, intervalTime)
}

 let answerOne = prompt('Do you want to go to a fancy dinner tonight to celebrate our love?... yes or no?').toLowerCase();

  if (answerOne === 'yes' || answerOne === 'y') {
    console.log('yes, thats correct');
    alert('Great its a late daye! See you at 930!');
    playerScore++;
  } else if (answerOne === 'no' || answerOne === 'n') {
    console.log('Sorry, you are wrong');
    alert(' Oh well were going anyway...cant wait to see you dressed up! 930!!');
  } else {
    console.log('follow instructions');
    alert('Please follow instructions and answer with a yes/no!');
  }
}

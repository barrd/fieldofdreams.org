function formClear() {
  var bgCol = '#fde4ff';
  if (document.getElementById('vContact')) {
    var field = document.getElementById('vContact');
    field.cName.style.backgroundColor = bgCol;
    field.cEmail.style.backgroundColor = bgCol;
    field.cMessage.style.backgroundColor = bgCol;
  }
}
function formCheck() {
  var errBgCol = '#fde772';
  var bgCol    = '#fde4ff';
  if (document.getElementById('vContact')) {
    var form = document.getElementById('vContact');
    form.cName.style.backgroundColor = bgCol;
    form.cEmail.style.backgroundColor = bgCol;
    form.cMessage.style.backgroundColor = bgCol;
    if (form.cName.value == '' || form.cName.value == ' ') {
      alert('Please enter your name.');
      form.cName.focus();
      form.cName.style.backgroundColor = errBgCol;
      return false;
    }
    else {
      form.cName.style.backgroundColor = bgCol;
    }
    if (form.cEmail.value == '' || form.cEmail.value == ' ') {
      alert('Please enter your eMail address.');
      form.cEmail.focus();
      form.cEmail.style.backgroundColor = errBgCol;
      return false;
    }
    else {
      form.cEmail.style.backgroundColor = bgCol;
    }
    if (form.cMessage.value == '' || form.cMessage.value == ' ') {
      alert('Please write a Message.');
      form.cMessage.focus();
      form.cMessage.style.backgroundColor = errBgCol;
      return false;
    }
    else {
      form.cMessage.style.backgroundColor = bgCol;
    }
  }
  return true;
}

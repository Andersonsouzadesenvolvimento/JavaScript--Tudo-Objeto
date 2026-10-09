const menu = {
  selector: '.principal',

  active() {
    const menuElement = document.querySelector(this.selector);

    if (menuElement) {
      menuElement.classList.add('active');
    }
  },
};

menu.active();

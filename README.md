composer require tightenco/Ziggy
npm install ziggy-js
npm list ziggy-js
thêm vào app.js
import route from 'ziggy-js';
window.route = route;
 
thêm vào layout.blade.php trước script
@route
 
 
url: route("admin.variations.show", { id: this.globalVariationId }),
 

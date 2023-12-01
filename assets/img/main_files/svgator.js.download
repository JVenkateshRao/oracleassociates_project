function changeTarget(ev){
    var t = ev.target;
    if (t && t.host && t.host !== document.location.host) {
        if (!t.getAttribute('target')) {
            t.setAttribute('target', '_blank');
        }
    }
}

(document.addEventListener || document.attachEvent)('mousedown', changeTarget, {passive: true});
(document.addEventListener || document.attachEvent)('keydown', changeTarget, {passive: true});
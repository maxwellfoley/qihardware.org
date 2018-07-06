## Do you know more?

Please do help us add the latest knowledge to this guide.

<a href="{{ site.github.repository_url }}" class="button" style="background-color: #008CBA  ; border: none; color: white; padding: 12px 24px; text-align: center; text-decoration: none; display: inline-block; font-size: 16px; border-radius: 12px;">Edit now</a>

---

Last Modified At: {% last_modified_at %}
Page Last Modified At: {{ page.last_modified_at }}


Site Updated: {{ site.time | date: "%-d %B %Y" }} {% if include.mod_date %}. Page Updated: {{ include.mod_date | date: "%-d %B %Y" }} {% endif %} {% if site.github.is_project_page %}. [{{ site.github.repository_name }}]({{ site.github.repository_url }}) [by]({{ site.github.repository_url }}/blob/master/LICENSE) [{{ site.github.owner_name }}]({{ site.github.owner_url }}){% endif %}


<style>
  @media screen and (max-width: 992px) {
    .github-ribbon {
      display:none
    }
  }
</style>
